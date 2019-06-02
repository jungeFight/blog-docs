+++
title = "composer自动加载原理"
author = "sunrain"
github_url = "zunler.top"
head_img = ""
created_at = 2019-06-02T23:36:36
updated_at = 2019-06-02T23:36:36
description = "composer自动加载项目或者框架中用到的相应composer包的实现过程"
tags = ["linux", "php"]
+++

## composer自动加载原理

- 先初始加载两类文件：
   
   1. autoload.php加载

   2. autoload_real.php加载
   
   3. ClassLoader和autoload_static文件

+ classmap.php，files.php,namespaces.php返回的数组是file、psr4、classMap对应文件绝对地址的映射；

* autoload_static.php中通过dump-autoload会生成file、psr4、classMap对应的文件映射。$loader实现文件自动加载；

* 实现自动加载，spl_autoload_register中注册的多个文件加载函数根据生成的文件绝对路径对应的数组加载对应用到的文件；



### Markdown基本语法

<a href="https://www.jianshu.com/p/191d1e21f7ed" target="_blank">Markdown基本语法</a>

[简书测试](http://jianshu.com)