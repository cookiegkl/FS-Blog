<p align="center">
    <a href="http://fsblog.letec.top">
        <img width="200" src="screenshots/logo.png">
    </a>
</p>

# Blog



[![Build Status](https://www.travis-ci.org/JamesZBL/FS-Blog.svg?branch=master)](https://www.travis-ci.org/JamesZBL/FS-Blog)
[![LICENSE](https://img.shields.io/badge/license-Apache%202-brightgreen.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
![GitHub release](https://img.shields.io/github/release/jameszbl/fs-blog.svg)


## 基于 Spring Boot 的博客系统


### 1. 涉及技术及工具

- 核心框架：SpringBoot
- ORM 框架：MyBatis
- MyBatis 工具：MyBatis Mapper 
- MVC 框架：Spring MVC
- 模板引擎：Freemarker
- 编译辅助插件：Lombok
- CSS 框架：BootStrap 4.0
- Markdown 编辑器：Editor.md
- 数据库：MySQL


### 2. 构建及运行

#### 2.1 服务器环境

- 安装 ``MySQL``
- 安装 ``Gradle``
- 在项目目录下运行 ``gradle clean build``，生成的 jar 包位于 ``build/libs`` 目录下，使用 ``java -jar .../fsblog.jar`` 运行
- 在 ``application-dev.yml`` 中配置数据库用户名和密码，默认为：``username: root password: root``
- 默认自动创建数据库、数据表并自动导入初始数据，同样在``application-dev.yml``中配置
- 后台管理默认用户名为 ``admin``，密码为 ``123456``

### 3. 开源协议

[Apache License 2.0](http://apache.org/licenses/LICENSE-2.0.html)

Copyright (c) 2019-present, Alex