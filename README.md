# 36tz_cn_193
Node.js+Express+Koa2+开发Web Server博客
Node.js+Express+Koa2+开发Web Server博客
👇👇👇👇👇👇👇👇点击下载地址👇👇👇👇👇👇👇
[![download](https://51xueit.vip/muke_img/5fd18ee309404a9a05400304.jpg "下载地址")](http://www.36tz.cn "下载地址")
### 第1章 课程介绍 

#### 包括课程概述、核心模块、核心技术、课程安排、课程收获、讲授方式、学习前提等方面的介绍，让同学们对课程项目有一个直观的了解。
1-1 课程导读 (07:01)

1-2 课程适用于最新版node.js (02:08)


### 第2章 nodejs 介绍

#### 本章主要为了照顾尚未入门或者刚刚入门 nodejs 的同学，介绍 nodejs 的下载、安装和基本使用，以及 nodejs 和前端 javascript 的区别。另外，重点介绍了服务端开发和前端开发思路上的区别，为后续的开发做一个基础的铺垫。
2-1 下载和安装 (05:47)

2-2 nodejs和js的区别 (06:54)

2-3 commonjs-演示 (08:27)

2-4 debugger (09:07)

2-5 debuger之inspect协议 (09:37)

2-6 server端和前端的区别 (14:58)

2-7 总结 (02:31)


### 第3章 项目介绍

#### 课程是通过案例的形式来学习 nodejs ，本章先来介绍这个案例，即个人博客项目。包括需求分析、原型图设计、以及 server 端的技术方案设计。有了详细的设计方案，才能指导后续的实际开发。
3-1 项目需求分析 (09:21)

3-2 技术方案 (11:51)


### 第4章 开发博客项目之接口 

#### 要开发一个博客项目的 server 端，首先要实现技术方案设计中的各个 API 。本章主要讲解如何使用原生 nodejs 处理的 http 请求，包括路由分析和数据返回，然后代码演示各个 API 的开发 。但是本章尚未连接数据库，因此 API 返回的都是假数据。...
4-1 http-概述 (11:44)

4-2 处理get请求 (13:23)

4-3 处理post请求 (12:28)

4-4 处理http请求的综合示例 (08:31)

4-5 搭建开发环境 (15:28)

4-6 初始化路由 (17:48)

4-7 开发路由（博客列表路由）（上） (18:08)

4-8 开发路由（博客详情路由）（下） (17:53)

4-9 开发路由（处理 POSTData） (07:53)

4-10 开发路由（新建和更新博客路由） (10:59)

4-11 开发路由（删除博客路由和登录路由） (08:32)

4-12 补充：路由和API (03:24)


### 第5章 开发博客项目之数据存储

#### API 实现了，就需要连接数据库，实现真正的数据存储和查询，不再使用假数据。本章主要讲解 mysql 的安装、使用，以及用 nodejs 连接 mysql ，最后将 mysql 应用到各个已经开发完的 API 中。
5-1 MySql 介绍 (07:47)

5-2 数据库操作（创建和增、删、查） (21:58)

5-3 数据库操作（更新） (18:12)

5-4 nodejs操作 mysql (10:07)

5-5 nodejs 链接 mysql 做成工具 (09:58)

5-6 API对接mysql（博客列表） (13:20)

5-7 API对接mysql（博客详情和新建） (13:54)

5-8 API对接mysql（博客更新和删除） (11:50)

5-9 API对接mysql（登录） (07:39)

5-10 总结 (01:48)


### 第6章 博客项目之登录

#### 用户登录是博客项目的主要功能之一，本章主要讲解如何使用原生 nodejs 实现登录。包括 cookie session 的介绍和使用，以及为了扩展性和性能使用 redis 来存储 session 。最后，通过 nginx 配置联调环境，和前端页面联调。本章内容较多，对于前端开发人员来说，新概念也较多，是本课程学习上的挑战。...
6-1 开始 (05:36)

6-2 cookie-介绍 (13:54)

6-3 cookie用于登录验证 (18:05)

6-4 cookie做限制（1） (04:15)

6-5 cookie做限制（2） (10:04)

6-6 session介绍 (13:57)

6-7 session演示 (08:50)

6-8 从 session 到 redis (16:16)

6-9 redis介绍 (05:30)

6-10 nodejs链接redis的demo (05:41)

6-11 nodejs连接redis-封装工具函数 (08:30)

6-12 session存入redis (12:11)

6-13 完成server端登录的代码 (07:10)

6-14 联调-介绍html页面 (08:03)

6-15 nginx配置 (13:12)

6-16 联调演示与总结 (10:07)


### 第7章 博客项目之日志

#### 日志记录和日志分析是 server 端的重要模块，前端涉及较少。本章主要讲解如何使用原生 nodejs 实现日志记录、日志内容分析和日志文件拆分。其中包括 stream readline 和 crontab 等核心知识点。
7-1 开始 (11:23)

7-2 nodejs文件操作 (10:28)

7-3 stream 介绍 (11:01)

7-4 stream演示（1） (06:54)

7-5 stream演示（2） (07:53)

7-6 写日志 (10:02)

7-7 拆分日志 (10:27)

7-8 分析日志介绍 (04:54)

7-9 readline演示 (05:53)

7-10 总结 (05:41)


### 第8章 博客项目之安全

#### 安全是 server 端需要考虑的重点内容，本章主要讲解 nodejs 如何防范 sql 注入，xss 攻击，以及数据库的密码加密 —— 以防被黑客获取明文密码。
8-1 开始和sql注入 (15:57)

8-2 xss攻击 (13:41)

8-3 密码加密和总结 (17:31)

8-4 统一总结 (11:56)


### 第9章 使用 express 重构博客项目

#### 先前的课程内容都是通过原生 nodejs 实现，是为了让同学们了解原理和底层实现，但实际开发还是会使用框架和工具来提高效率。本章使用 express 重构这个博客项目，学习使用框架和中间件机制。另外，本章将使用常用的插件来实现登录、日志等比较繁琐的功能，提高开发效率。最后，还详细讲解了 express 中间件的实现原理...
9-1 开始 (09:30)

9-2 express 安装 (12:27)

9-3 介绍express的入口代码 (21:02)

9-4 演示express如何处理路由 (12:11)

9-5 express中间件 (27:13)

9-6 express介绍的总结 (04:22)

9-7 express开发博客项目-初始化环境 (11:51)

9-8 express处理session (07:31)

9-9 session连接redis (13:32)

9-10 登录中间件 (05:21)

9-11 开发路由 (13:32)

9-12 介绍morgan (03:00)

9-13 使用morgan写日志 (17:57)

9-14 中间件原理介绍 (07:36)

9-15 中间件原理-代码实现 (31:25)

9-16 -总结 (04:01)


### 第10章 使用 Koa2 重构博客项目

#### 目前 koa2 和 express 是企业同时使用的 nodejs 框架，因此本章使用 koa2 再次重构这个博客项目。重构过程中将详细学习 koa2 框架的使用，koa2 的中间件机制，以及 async/await 语法。同理，本行也使用常用框架来实现登录、日志等比较繁琐的功能，提高开发效率。最后，还详细讲解了 koa2 中间件的实现原理，...
10-1 开始 (14:14)

10-2 介绍koa2 (12:18)

10-3 介绍路由 (11:04)

10-4 介绍中间件机制 (04:18)

10-5 实现session (10:09)

10-6 开发路由-准备工作 (11:16)

10-7 开发路由-代码演示 (12:02)

10-8 开发路由-（联调） (01:52)

10-9 日志 (07:52)

10-10 中间件原理-分析 (10:11)

10-11 中间件原理-代码演示 (15:21)

10-12 总结 (04:12)


### 第11章 上线与配置

#### 代码开发完毕要线上运行，并且保证服务稳定性，将使用 PM2 工具。本章讲解 PM2 的配置使用和进程守护，以及 PM2 多进程模型。最后，还介绍了服务器运维的相关方法。
11-1 开始和 PM2 介绍 (10:10)

11-2 常用命令 (08:14)

11-3 进程守护 (04:48)

11-4 常用配置 (08:45)

11-5 多进程 (06:29)

11-6 总结 (03:37)


### 第12章 课程总结

#### 对课程做总结，并列出了课程所提到的主要知识点，整体回顾课程。
12-1 课程总结 (03:57)

12-2 如何进阶nodejs (08:08)


### 第13章 数据库使用 mongodb 重构博客项目

#### 数据库使用 mongodb 重构博客项目
13-1 本章主要内容 (04:40)

13-2 mongodb是文档数据库 (18:59)

13-3 安装mongodb-介绍 (01:36)

13-4 安装mongodb-mac-安装homebrew (05:23)

13-5 安装mongodb-mac-安装mongodb (04:39)

13-6 安装mongodb-mac-安装compass (06:28)

13-7 安装mongodb-windows（1） (04:55)

13-8 安装mongodb-windows（2） (07:37)

13-9 安装mongodb-windows（3） (08:40)

13-10 用compass操作mongodb (13:41)

13-11 用命令行操作mongodb (13:27)

13-12 mongodb的几个重要概念 (08:05)

13-13 nodejs连接mongodb (12:00)

13-14 nodejs操作mongodb-part1 (16:28)

13-15 使用mongoose连接mongodb服务 (11:35)

13-16 mongoose的Schema和Model (10:00)

13-17 mongoose操作mongodb (16:36)

13-18 博客项目web-server链接mongodb服务端 (10:07)

13-19 博客项目web-server使用mognodb数据库 (16:52)

13-20 博客项目web-server使用mongodb-联调和测试 (12:30)

13-21 本章总结~ (03:21)


### 第14章 nodejs 面试真题讲解

#### nodejs 面试真题讲解
14-1 nodejs面试考点梳理-part1 (13:41)

14-2 nodejs是什么？和前端js有何区别？ (03:42)

14-3 【必考题】nodejs如何调试 (03:38)

14-4 commonjs和ES6-Module的区别 (06:39)

14-5 回顾浏览器event loop过程 (09:22)

14-6 【必考题】event loop在浏览器和nodejs的区别 (13:39)

14-7 异步代码场景题-考察你对nodejs异步编程的理解 (15:44)

14-8 session如何实现登录？ (04:38)

14-9 请描述koa2和express的中间件机制 (05:52)

14-10 请描述 koa2 洋葱圈模型 (03:52)

14-11 nodejs如何读取大文件？ (03:21)

14-12 nodejs线上环境为何开启多进程？ (02:34)


[下载地址](http://www.36tz.cn "下载地址")
