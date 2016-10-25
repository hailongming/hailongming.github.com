---
layout: post
title:  "jekyll+github pages 搭建个人博客"
date:   2016-10-25 16:47:58
categories: jekyll 
---
>  Jekyll 是一个静态站点生成器，它会根据网页源码生成静态文件。提供了模板、变量、插件等功能，所以实际上可以用来写整个网站。

### 先在本地编写符合 jekyll 规范的网站源码，然后上传到github， 由github生成并托管整个网站。

优点：
1.  免费
2. 用 git 来管理，不用担心丢失。
3. 支持markdown。
缺点：
-  有一定的技术门槛，需要懂一些网页知识和 git
- 只是静态网页，动态服务需要使用外部服务
- 没有数据库
但是用它来搭建博客还是很好的

###第一步 
安装ruby，因为jekyll是用Ruby语言写的。安装完成后运行下面的命令
` ~$gem install jekyll `
安装完成后运行` ~$jekyll -v`来检查是否安装成功
安装成功则运行`~$jekyll new blog`一个博客的基本构架就生成了。