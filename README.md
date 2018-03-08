# Spring Boot Guide

Spring Boot Reference Guide for 2.0.0.RELEASE


# I. Spring Boot 文档
## 1. 关于
## 2. 帮助
## 3. 第一步
## 4. Spring Boot 使用
## 5. Spring Boot 特性
## 6. 生产使用
## 7. 高级特性

# II. 入门
## 8. Spring Boot 介绍
## 9. 系统要求
### 9.1. Servlet 容器
## 10. Spring Boot 安装
### 10.1. Java 环境安装说明
#### 10.1.1. Maven 安装
#### 10.1.2. Gradle 安装
### 10.2. Spring Boot CLI 安装
#### 10.2.1. 手动安装
#### 10.2.2. SDKMAN 安装
#### 10.2.3. OSX Homebrew 安装
#### 10.2.4. MacPorts 安装
#### 10.2.5. Command-line 工作
#### 10.2.6. Spring CLI 入门示例
### 10.3. Spring Boot 旧版本升级
## 11. 开发你的第一个 Spring Boot 应用
### 11.1. 创建 POM
### 11.2. 添加类路径依赖关系
### 11.3. 绑定代码
#### 11.3.1. @RestController 和 @RequestMapping 注解
#### 11.3.2. @EnableAutoConfiguration 注解
#### 11.3.3. “main” 方法
### 11.4. 运行示例
### 11.5. 创建可执行 Jar 包
## 12. 接下来要阅读的内容



# I. Spring Boot 文档

本节主要是简要介绍Spring Boot参考文档。它作为文档其余部分的指引。

## 1. 关于

文档的形式：

* HTML
* PDF
* EPUB

>Copies of this document may be made for your own use and for distribution to others, provided that you do not charge any fee for such copies and further provided that each copy contains this Copyright Notice, whether distributed in print or electronically.

## 2. 帮助

如果您在Spring Boot遇到问题，我们希望能提供帮助。

## 3. 第一步

如果您正准备开始使用 Spring Boot 或 Spring ，请从以下主题开始:

* 从头开始: Overview | Requirements | Installation
* 教程: Part 1 | Part 2
* 运行例子: Part 1 | Part 2

## 4. Spring Boot 使用

准备好真正开始使用 Spring Boot 吗？

* 构建工具: Maven | Gradle | Ant | Starters
* 最佳实践: Code Structure | @Configuration | @EnableAutoConfiguration | Beans and Dependency Injection
* 运行你的代码: IDE | Packaged | Maven | Gradle
* 打包应用: Production jars
* Spring Boot CLI: Using the CLI

## 5. Spring Boot 特性

需要更多关于 Spring Boot 核心功能的细节？ 为你准备了以下内容:

* 核心特性: SpringApplication | External Configuration | Profiles | Logging
* Web 应用: MVC | Embedded Containers
* 使用数据库: SQL | NO-SQL
* 消息: Overview | JMS
* 测试: Overview | Boot Applications | Utils
* 扩展: Auto-configuration | @Conditions

## 6. 生产使用

当你准备部署你的 Spring Boot 应用到生产环境中, 我们有一些你可能会喜欢的技巧:

* 管理端点: Overview | Customization
* 连接选项: HTTP | JMX
* 监控: Metrics | Auditing | Tracing | Process

## 7. 高级特性

最后, 我们为高级用户提供了一些特性:

* Spring Boot 应用部署: Cloud Deployment | OS Service
* 构建工具: Maven | Gradle
* 附录: Application Properties | Auto-configuration classes | Executable Jars


# II. 入门

如果您正准备开始使用Spring Boot，或者使用“Spring”，请先阅读本节。

它回答了基本的“what？”，“how？”和“why？”的问题。它包括Spring Boot的介绍以及安装说明。

然后，我们将引导您构建您的第一个Spring Boot应用程序，并在讨论一些核心原则。

## 8. Spring Boot 介绍

Spring Boot可以轻松创建可独立运行的、生产级的基于Spring的应用程序。我们对Spring平台和第三方库采取自己的解决方案，以便您少遇问题。大多数Spring Boot应用程序只需要很少的Spring配置。 您可以使用Spring Boot来创建一个java应用程序，这个应用程序可以使用 `java -jar` 或更传统的 war 包部署启动。我们还提供了一个运行“spring scripts”的命令行工具。

我们的主要目标是:

* 为所有Spring开发提供一个更快，更广泛的入门体验。
* 提供开箱即用的默认配置，但这些默认配置可随需求变化而改动。
* 提供大型项目通用的一系列非功能性功能。（如嵌入式服务器，安全性，指标，运行状况检查和外部配置）
* 绝对不会生成代码，并且不需要XML配置。

## 9. 系统要求

### 9.1. Servlet 容器
## 10. Spring Boot 安装
### 10.1. Java 环境安装说明
#### 10.1.1. Maven 安装
#### 10.1.2. Gradle 安装
### 10.2. Spring Boot CLI 安装
#### 10.2.1. 手动安装
#### 10.2.2. SDKMAN 安装
#### 10.2.3. OSX Homebrew 安装
#### 10.2.4. MacPorts 安装
#### 10.2.5. Command-line 工作
#### 10.2.6. Spring CLI 入门示例
### 10.3. Spring Boot 旧版本升级
## 11. 开发你的第一个 Spring Boot 应用
### 11.1. 创建 POM
### 11.2. 添加类路径依赖关系
### 11.3. 绑定代码
#### 11.3.1. @RestController 和 @RequestMapping 注解
#### 11.3.2. @EnableAutoConfiguration 注解
#### 11.3.3. “main” 方法
### 11.4. 运行示例
### 11.5. 创建可执行 Jar 包
## 12. 接下来要阅读的内容