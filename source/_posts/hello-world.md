---
title: 利用Hexo搭建个人博客
categories: 学习
---
本来打算在开学前做一个项目准备实习，在找项目的过程中发现别人的学习博客，觉得很酷，所以自己也想做一个，做完之后总结一下搭建过程，并将此博客作为个人学习记录博客！

### 准备工作

需要在电脑上安装git和node.js（应至少为 Node.js 10.13，建议为 12.0 或更高版本）

### 安装

新建一个文件夹，命名为Hexo

在Hexo目录下打开命令行窗口，执行以下指令：

`	npm install hexo-cli -g`

`	hexo init blog`

`	cd blog`

`	npm install`

`	hexo server`

此时你打开本地4000端口，已经可以发现属于你的博客了。

### 打包

<!--more-->

将文件打包生成静态资源，执行以下命令，将会生成public文件夹，里面存放静态资源，后续将博客部署到github上时，上传的也是静态文件（不直接更改里面的代码）。

`hexo g`

### 主题安装

[主题(hexo.io)](https://hexo.io/themes/)

在上面找到自己喜欢的主题并进入主题给出的github界面，那里会教你安装使用对应主题。

### 部署博客

部署博客到远端github(参考以下两篇文章)

[ 免费部署个人博客到远端GitHub（输密码有问题看下面博客）](https://blog.csdn.net/MarkeyMark/article/details/108179312)

[解决第一篇博客的问题](https://blog.csdn.net/qq_50840738/article/details/125087816)
