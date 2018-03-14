## Chatroom
PHP + Swoole 开发的简单聊天室demo, 主要是 websockt 的应用 。

## 环境要求
* PHP >= 7.0
* Swoole
* composer
## 安装
```
git clone https://github.com/kesixin/Chatroom
composer install
```

## 启动 websockt
```
cd ./webim
php webim_server.php
```

## 启动 PHP 内置服务器
```
cd ./public
php -S localhost:8000
```
浏览器访问 localhost:8000 即可进入聊天

## 截图
![webim](https://github.com/kesixin/Chatroom/blob/master/%E6%95%88%E6%9E%9C.jpg)

## License
MIT
