# openlib

---

[openlib](https://github.com/longniao/openlib) 是一个基于composer安装的基础类库，是 [yaframe](https://github.com/longniao/yaframe) 框架的一部分。




## 1. 安装composer

```
curl -s http://getcomposer.org/installer | php
```

## 2. 安装代码类库


```
cd ./openlib
php composer.phar install
```

## 3. 更新代码

`更新代码时要忽略项目.git目录，不然提交到私有仓库（如gitlab）时会出问题。`

```
composer update --prefer-dist
```

---

## composer类库说明

| 类库                            |  说明                      |
| :----------------------------- | :------------------------- |
| unicodeveloper/laravel-emoji   |  emoji表情,源自laravel框架   |
| illuminate/database            |  illuminate ORM框架         |
| illuminate/events              |  illuminate ORM依赖库       |
| symfony/debug                  |  illuminate ORM依赖库       |
| symfony/var-dumper             |  illuminate ORM依赖库       |
| filp/whoops                    |  PHP错误处理框架             |
| nette/mail                     |  邮件发送类库                |
| predis/predis                  |  PHP Redis 客户端类库        |
| chrisboulton/php-resque        |  PHP队列类库                 |
| monolog/monolog                |  PHP日志工具                 |
| phpunit/phpunit                |  PHP测试框架                 |
| hprose/hprose                  |  基于swoole扩展的RPC框架      |
| overtrue/wechat                |  微信公众平台 SDK             |
| nmred/kafka-php                |  基于kafka的php客户端         |
| phpseclib/phpseclib            |  PHP安全通信类库              |
| guzzlehttp/guzzle              |  PHP HTTP 客户端和框架        |
| lox/xhprof                     |  PHP性能分析工具              |
| imagine/imagine                |  PHP图像处理库                |
| dompdf/dompdf                  |  HTML to PDF converter      |
| knplabs/knp-snappy             |  PDF处理库                   |
| smalot/pdfparser               |  PDF解析库                   |
| phpoffice/phpword              |  PDF转换WORD                |