---
layout: page
title:  "个人笔记"
subtitle: "对知识有更详细的解释"
date:   2016-05-20 21:21:21 +0530
categories: ["学无止境"]
---
# 搭建个人技术博客

> 使用 GitHub Pages + Jekyll 快速部署个人博客

 - GitHub Pages 
   - 定义：GitHub网站给所有用户提供了一个个人主页
    - 如何访问：个人域名：用户名.github.io
   - 如何编写主页：建立一个用域名为项目名的远程版本仓库，只需要向该远程版本仓库中的master分支提交代码即可(该代码中必须用一个文件为index.html文件)
 - Jekyll 
    - 定义：可以将markdow语法自动编译为HTM语法的一个工具
    - 安装：不需要自己安装，在GitHub网站当中预安装的
    - 使用：不用人为的使用，当你请求个人域名的时候，GitHub服务器会读取仓库（以个人域名命名的那个远程版本库）中的master分支中的代码，如果该代码为markdow语法会自动调用Jekyll将其编译为HTML代码并返回客户端

- 建立一个以个人域名为项目名的远程版本仓库
- 访问一个网址：主题为：http://jekyllthemes.org/ 选择一个主题，将其代码复制到仓库中的master分支
- 以上两步可以合成一步，在主题仓库中点击fork，点击setting设置仓库名即可
- 将远程版本库中的代码克隆到本地
    - 从远程版本库克隆下来的代码会自动创建本地版本仓库
- 修改配置文件以及页面内容
- 书写博客

# 复制别人主页快捷操作
- 进入网址:https://github.com/knhash/Pudhina => 点击Fork =>   setting =>重命名(用户名：github.io)

## 网络请求
---

### 完整URL：
- 协议：客户端与服务端规定好的一种请求的规则
    - 客户端：发送请求的软件
    - 服务端：接收请求的软件
- 域名:ip的别名
    - 前缀：一般www作为主域名
    - 后缀：子域名
- 端口：为一个软件的运行提供一个入口
    - 请求(域名)->电脑->webServer(监听某端口)->请求通过
    - http协议的默认端口是80 https协议的默认端口是433
- 文件路径：
    - 入口文件：webServer配置入口文件的名字，这样访问一个目录 就可以访问到这个文件（默认文件）
- 参数：问好后

## 访问博客

- 1.去本地host文件中寻找域名与IP的映射关系(一对一)(本地域名解析)
- 在本地hosts文件(C:\Windows\System32\drivers\etc)中书写的ip和域名的关系为静态路由
    - 本地hosts文件添加静态路由关系，访问个人博客: 
    - 140.82.114.3 github.com
    - 185.199.109.153 le1212123.github.io
- 2.找不到去DNS服务器找(DNS域名解析)

{% comment %}
Might you have an include in your theme? Why not try it here!
{% include my-themes-great-include.html %}
{% endcomment %}

No laudem altera adolescens has, volumus lucilius eum no. Eam ei nulla audiam efficiantur. Suas affert per no, ei tale nibh sea. Sea ne magna harum, in denique scriptorem sea, cetero alienum tibique ei eos. Labores persequeris referrentur eos ei.
