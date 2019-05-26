+++
title = "计划写一个现代的php框架"
author = "sunrain"
github_url = "http://zunler.com"
head_img = ""
created_at = 2019-05-26T23:45:46
updated_at = 2019-05-26T23:45:46
description = "现代php的框架"
tags = ["php"]
+++

## php框架

框架中应该有的东西，统一入口，自动加载，支持composer，支持扩展，各种设计模式的封装

```php
    function autoload($class) 
    {
        require($dir . $class);
    }
    spl_autoload_register('autoload');

```

` php laravel mysql yii go blog`


