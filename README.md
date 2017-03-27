## BE
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

This repository introduces how to perform backend development.

服务端开发，也有的叫后端开发，主要是接受客户端（Android, iOS等）或者前端请求（根据约定协议可能是HTTP请求或者TCP请求），或进行业务逻辑计算，或操作数据库（mysql, mongodb, redis等），或调用其他接口，然后返回消息（格式根据协议可能是JSON，XML或者序列化数据流等）给客户端或者前端。

### 语言
服务端的语言比较多，用的比较多的有C/C++，Java，PHP，Python，Ruby，Go，.NET，Javascript(NodeJS)等，每个语音各有自己的优点和缺点，本文主要介绍Java在服务端的技术栈。

### Java
#### Basic
- Basic type(byte, boolean, char, int, short, long, float, double)
- String
- Flow control(if, else, while, for, switch, break)
- IO stream
- Collection(Map, List, Set)
- JVM/GC
- Multi-thread/Lock

#### Framework
- Spring [官网](https://spring.io/)
- Spring MVC
- Spring Boot [官网](https://projects.spring.io/spring-boot/) [我的笔记和示例代码](https://github.com/luffyke/springboot-demo)

#### ORM
- Mybatis, [官网](http://www.mybatis.org/mybatis-3/), [Mybatis产品](http://blog.mybatis.org/p/products.html)

### OS
- Linux [我的笔记](https://github.com/luffyke/notes/tree/master/linux)

### Network protocal
- 互联网协议入门 [01](http://www.ruanyifeng.com/blog/2012/05/internet_protocol_suite_part_i.html) [02](http://www.ruanyifeng.com/blog/2012/06/internet_protocol_suite_part_ii.html)
- HTTP
- TCP

### Transfer method
- RPC(远程过程调用)
- Rest

### Transfer data structure
- [JSON](http://www.json.org/json-zh.html)
- XML

### Source control
- Git

### Server
- Nginx [我的笔记](https://github.com/luffyke/notes/tree/master/nginx)
- Tomcat

### 存储
- Mysql [我的笔记](https://github.com/luffyke/notes/tree/master/mysql)
- MongoDB [我的笔记](https://github.com/luffyke/notes/tree/master/mongo)
- Redis