---
layout: page
title:  "020年9月9日笔记"
date:   2020-09-10 17:44:44 +0530
categories: ["笔记文章"]
---
# 搭建个人博客

> GitHub Pages + Jekyll 快速部署个人博客
> - GitHub Pages:
>     - 定义：给所有的注册用户提供了一个个人主页
>     - 如何访问：域名：用户名.github.io
>     - 如何编写主页：建立一个用个人域名为项目名的远程版本仓库，只需要该远程版本仓库中的master分支提交代码即可(该代码中必须有一个文件叫index.html文件)

> - Jekyll：
>     - 定义：可以将markdow语法自动编译成html语法的一个工具
>     - 安装：不需要自己安装，在github网站当中预安装了
>     - 使用：也不用我们人为去使用，但你请求个人域名的)时候，github服务器会读取仓库(以个人域名命名的那个远程管理仓库中的master分支中的代码，如果该代码为markdow语法会自动调用jekyll将其编译为html并返回客户端

- 建立一个以个人域名为项目名的远程版本仓库
- 访问一个网址：主题网址：http://jekyllthemes.org/ 选择一个主题将其代码复制到我们的仓库中的master分支中
- 以上的两部可以合并为一步，在主题仓库中点击fork，点击setting设置仓库名即可
- 将远程版本库中的代码克隆到本地
    -   点击头像，点code，复制链接
    -   在文件打开终端执行克隆：'git clone -b master https://github.com/yemo0205/yemo0205githubio.git myBlog'
    -从远程版本库中克隆下来的代码会自动创建本地版本仓库
- 修改配置文件以及页面内容
- 书写博客