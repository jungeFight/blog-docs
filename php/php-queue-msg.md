+++
title = "php开发方式"
author = "sunrain"
github_url = "zunler.top"
head_img = ""
created_at = 2017-04-19T02:19:36
updated_at = 2017-04-19T02:19:36
description = "记录了php中异步进程用消息队列通讯的方式"
tags = ["linux", "php"]
+++

## 各种开发通讯方式

  常驻内存的进程 -> 接收消息消费后 -> 再通知其他消息处理；

  `supervisor进程管理，kafuka，常驻内存的进程`

## 流程

- 爬虫爬取

    通知更新