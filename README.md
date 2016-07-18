
=================

用于新浪微博开放平台的PHP SDK. 内含能直接使用的DEMO.

forked from xiaosier/libweibo

修改使其符合PSR4

composer
-----
composer.phar require n3yang/libweibo:dev-master

更新
-----
+ 删除 OAuthException，改为 Exception
+ 独立类到不同文件
+ 增加 composer auto load