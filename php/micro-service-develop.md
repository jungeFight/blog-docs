+++
title = "php微服务化的方式开发"
author = "sunrain"
github_url = "zunler.top"
head_img = ""
created_at = 2019-05-28T21:28:36
updated_at = 2019-05-28T21:26:36
description = "项目可以分开部署，依赖通过http方式通信"
tags = ["linux", "php"， "wrk", "ab", "jmeter"]
+++

## 不同项目依赖一个数据提供中心datapai

- 项目都可以单独部署，每个项目都是单独的MVC的方式，分为：

    app项目
    
    微信项目
    
    管理后台项目
    
    命令行进程项目

    数据提供方项目，操作数据库

- 模块化开发的方式：

    模块间项目依赖，不同项目可以分开部署，但是代码都是同一套，可以只提供自己项目相关的服务。
