# Git使用指南

## 1.Git简介

Git是目前世界上最先进的分布式版本控制系统（没有之一）。



## 2.在Windows上安装Git

在Windows上使用Git，可以从Git官网直接[下载安装程序](https://git-scm.com/downloads)，然后按默认选项安装即可。

安装完成后，在开始菜单里找到“Git”->“Git Bash”，蹦出一个类似命令行窗口的东西，就说明Git安装成功！

![1572692102264](C:\Users\Frank\AppData\Roaming\Typora\typora-user-images\1572692102264.png)

安装完成后，还需要最后一步设置，在命令行输入：

> ```bash
> $ git config --global user.name "Your Name"
> $ git config --global user.email "email@example.com"
> ```

因为Git是分布式版本控制系统，所以，每个机器都必须自报家门：你的名字和Email地址。你也许会担心，如果有人故意冒充别人怎么办？这个不必担心，首先我们相信大家都是善良无知的群众，其次，真的有冒充的也是有办法可查的。

注意`git config`命令的`--global`参数，用了这个参数，表示你这台机器上所有的Git仓库都会使用这个配置，当然也可以对某个仓库指定不同的用户名和Email地址。

## 3.