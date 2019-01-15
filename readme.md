
## Laravel-starter

Laravel-starter 是 Laravel 5.7 的快速创建脚手架

## 功能特性

- 中文配置
- 基本页面布局
- 用户认证

## 环境要求

**Laravel** 版本为 **5.7**，相关基本环境要求请参考Laravel官方文档

## 安装

```
$ git clone https://github.com/pigzzz123/laravel-starter.git
$ cd laravel-starter
$ cp .env.example .env
$ composer install
$ php artisan key:generate
$ npm install
$ npm run watch-poll
```

修改数据库配置，数据迁移

```
$ php artisan migrate
```

建立文件系统的**软链接**

```
$ php artisan storage:link
```
