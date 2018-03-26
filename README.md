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

# III. 使用 Spring Boot
## 13. 构建
### 13.1. 依赖管理
### 13.2. Maven
#### 13.2.1. 继承 Starter Parent
#### 13.2.2. 使用 Spring Boot 不依赖父 POM
#### 13.2.3. 使用 Spring Boot Maven 插件
### 13.3. Gradle
### 13.4. Ant
### 13.5. Starters

## 14. 组织你的代码
### 14.1. 使用“默认”包
### 14.2. 查找主要应用程序类

## 15. 配置类
### 15.1. 导入其他配置类
### 15.2. 导入 XML 配置

## 16. Auto-configuration
### 16.1. 逐渐替换 Auto-configuration
### 16.2. 禁用特定的 Auto-configuration 类

## 17. Spring Beans 和依赖注入
## 18. 使用 @SpringBootApplication 注解
## 19. 运行你的应用
### 19.1. 使用 IDE 运行
### 19.2. 运行打包应用
### 19.3. 使用 Maven 插件
### 19.4. 使用 Gradle 插件
### 19.5. 热交换

## 20. 开发工具
### 20.1. 属性默认值
### 20.2. 自动重启
#### 20.2.1. 记录条件评估中的更改
#### 20.2.2. 排除资源
#### 20.2.3. 观察额外的路径
#### 20.2.4. 禁用重新启动
#### 20.2.5. 使用触发文件
#### 20.2.6. 自定义重启类加载器
#### 20.2.7. 已知限制
### 20.3. 实时加载
### 20.4. 全局设置
### 20.5. 远程应用
#### 20.5.1. 运行远程客户应用
#### 20.5.2. 远程更新

## 21. 为生产环境打包应用
## 22. 接下来要阅读的内容

# IV. Spring Boot功能 
## 23. SpringApplication 
### 23.1. 启动失败 
### 23.2. 自定义Banner 
### 23.3. 自定义SpringApplication 
### 23.4. Fluent Builder API 
### 23.5. 应用程序事件和监听器 
### 23.6. Web环境
### 23.7. 访问应用程序参数 
### 23.8. 使用ApplicationRunner或CommandLineRunner 
### 23.9. 申请退出 
### 23.10. 管理功能

## 24. 外部化配置
### 24.1. 配置随机值
### 24.2. 访问命令行属性
### 24.3. 应用程序属性文件
### 24.4. 配置文件特定的属性
### 24.5. 属性中的占位符
### 24.6. 使用 YAML 文件代替 Properties 文件
#### 24.6.1. 加载 YAML
#### 24.6.2. 在Spring环境中展示YAML文件
#### 24.6.3. 多环境 YAML 文件
#### 24.6.4. YAML 缺点
#### 24.6.5. 合并 YAML 列表
### 24.7. 类型安全的配置属性
#### 24.7.1. 第三方配置
#### 24.7.2. 轻松的绑定
#### 24.7.3. 属性转换和转换时间 
#### 24.7.4. @ConfigurationProperties Validation
#### 24.7.5. @ConfigurationProperties vs. @Value

## 25. Profiles 
### 25.1. 添加活动配置文件 
### 25.2. 编程设置配置文件 
### 25.3. 配置文件特定的配置文件 

## 26.日志 
### 26.1. 日志格式 
### 26.2. 控制台输出 
#### 26.2.1. 彩色编码输出 
### 26.3. 文件输出 
### 26.4. 日志级别 
### 26.5. 自定义日志配置 
### 26.6. Logback扩展 
#### 26.6.1. 配置文件特定的配置 
#### 26.6.2. 环境属性


## 27.开发Web应用程序 
### 27.1. Spring Web MVC框架
#### 27.1.1. Spring MVC自动配置 
#### 27.1.2. HttpMessageConverters 
#### 27.1.3. 自定义JSON序列化器和反序列化器 
#### 27.1.4. MessageCodesResolver
#### 27.1.5. 静态内容 
#### 27.1.6. 欢迎页面 
#### 27.1.7. 自定义Favicon 
#### 27.1.8. 路径匹配和内容协商 
#### 27.1.9. ConfigurableWebBindingInitializer 
#### 27.1.10. 模板引擎 
#### 27.1.11. 错误处理 自定义错误页面 在Spring MVC之外映射错误页面 
#### 27.1.12. Spring HATEOAS 
#### 27.1.13. CORS支持 

### 27.2. Spring WebFlux框架
#### 27.2.1. Spring WebFlux自动配置 
#### 27.2.2. 使用HttpMessageReaders和HttpMessageWriters的HTTP编解码器 
#### 27.2.3. 静态内容 
#### 27.2.4. 模板引擎 
#### 27.2.5. 错误处理 自定义错误页面 
#### 27.2.6. 网页过滤器 

### 27.3. JAX-RS 和 Jersey
### 27.4. 嵌入式Servlet容器支持 
#### 27.4.1. Servlet，过滤器和监听器 将Spring Servlet，过滤器和监听器注册为Spring Bean 
#### 27.4.2. Servlet上下文初始化 扫描Servlet，筛选器和侦听器 
#### 27.4.3. ServletWebServerApplicationContext 
#### 27.4.4. 定制嵌入式Servlet容器 程序化定制 直接自定义ConfigurableServletWebServerFactory 
#### 27.4.5. JSP限制

# 28. 安全 
## 28.1. MVC安全 
## 28.2. WebFlux安全 
## 28.3. OAuth2 
### 28.3.1. 客户端 
## 28.4. Actuator 安全 
### 28.4.1. 跨站请求伪造保护

## 29.使用SQL数据库 
### 29.1. 配置一个数据源 
#### 29.1.1. 嵌入数据库支持 
#### 29.1.2. 连接到生产数据库 
#### 29.1.3. 连接到JNDI数据源 
### 29.2. 使用JdbcTemplate 
### 29.3. JPA和“Spring Data” 
#### 29.3.1. 实体类 
#### 29.3.2. Spring Data JPA存储库 
#### 29.3.3. 创建和删除JPA数据库 
#### 29.3.4. 在View中打开EntityManager 
### 29.4. 使用H2的Web控制台 
#### 29.4.1. 更改H2 Console的路径 
### 29.5. 使用jOOQ 
#### 29.5.1. 代码生成 
#### 29.5.2. 使用DSLContext 
#### 29.5.3. jOOQ SQL方言 
#### 29.5.4. 定制jOOQ

## 30.使用 NoSQL 技术 

### 30.1. Redis 
#### 30.1.1. 连接到Redis 

### 30.2. MongoDB 
#### 30.2.1. 连接到MongoDB数据库 
#### 30.2.2. MongoTemplate 
#### 30.2.3. Spring Data MongoDB存储库 
#### 30.2.4. 嵌入式Mongo 

### 30.3. Neo4j 
#### 30.3.1. 连接到Neo4j数据库 
#### 30.3.2. 使用嵌入式模式 
#### 30.3.3. Neo4jSession 
#### 30.3.4. Spring Data Neo4j存储库 
#### 30.3.5. 存储库示例 

### 30.4. GemFire
 
### 30.5. Solr 
#### 30.5.1. 连接到Solr 
#### 30.5.2. Spring Data Solr存储库 

### 30.6. Elasticsearch 
#### 30.6.1. 使用Jest连接到Elasticsearch 
#### 30.6.2. 通过使用Spring Data 连接到Elasticsearch 
#### 30.6.3. Spring Data Elasticsearch存储库 

### 30.7. Cassandra
#### 30.7.1. 连接到Cassandra 
#### 30.7.2. Spring Data Cassandra存储库 

### 30.8. Couchbase 
#### 30.8.1. 连接到Couchbase 
#### 30.8.2. Spring Data Couchbase存储库 

### 30.9. LDAP 
#### 30.9.1. 连接到LDAP服务器 
#### 30.9.2. Spring数据LDAP存储库 
#### 30.9.3. 嵌入式内存LDAP服务器 

### 30.10. InfluxDB 
#### 30.10.1. 连接到InfluxDB

## 31.缓存 
### 31.1. 支持的缓存提供程序 
#### 31.1.1. 通用 
#### 31.1.2. JCache（JSR-107） 
#### 31.1.3. EhCache 2.x 
#### 31.1.4. Hazelcast 
#### 31.1.5. Infinispan
#### 31.1.6. Couchbase 
#### 31.1.7. Redis
#### 31.1.8. Caffeine
#### 31.1.9. Simple 
#### 31.1.10. None

## 32.信息 
### 32.1. JMS 
#### 32.1.1. ActiveMQ支持 
#### 32.1.2. Artemis支持 
#### 32.1.3. 使用JNDI ConnectionFactory 
#### 32.1.4. 发送消息 
#### 32.1.5. 接收消息 

### 32.2. AMQP 
#### 32.2.1. RabbitMQ支持 
#### 32.2.2. 发送消息 
#### 32.2.3. 接收消息 

### 32.3. Apache Kafka 
#### 32.3.1. 发送消息 
#### 32.3.2. 接收消息 
#### 32.3.3. 额外的 Kafka 属性

## 33.用RestTemplate调用REST服务 
### 33.1. RestTemplate自定义 

## 34.使用WebClient调用REST服务 
### 34.1. WebClient自定义 

## 35.验证 

## 36.发送电子邮件 

## 37.与JTA的分布式事务 
### 37.1. 使用Atomikos事务管理器 
### 37.2. 使用Bitronix事务管理器 
### 37.3. 使用Narayana事务管理器 
### 37.4. 使用Java EE托管事务管理器 
### 37.5. 混合XA和非XA JMS连接 
### 37.6. 支持替代嵌入式事务管理器


## 38. Hazelcast
## 39. Quartz Scheduler
## 40. Spring Integration
## 41. Spring Session
## 42. 监控和管理 JMX


## 43.测试 
### 43.1. 测试范围依赖关系 
### 43.2. 测试Spring应用程序 
### 43.3. 测试Spring Boot应用程序 
#### 43.3.1. 检测Web应用程序类型 
#### 43.3.2. 检测测试配置 
#### 43.3.3. 排除测试配置 
#### 43.3.4. 使用运行的服务器进行测试 
#### 43.3.5. Mocking 和 Spying Beans
#### 43.3.6. 自动配置的测试 
#### 43.3.7. 自动配置的JSON测试 
#### 43.3.8. 自动配置的Spring MVC测试 
#### 43.3.9. 自动配置的Spring WebFlux测试 
#### 43.3.10. 自动配置的数据JPA测试 
#### 43.3.11. 自动配置的JDBC测试 
#### 43.3.12. 自动配置的jOOQ测试 
#### 43.3.13. 自动配置的数据MongoDB测试 
#### 43.3.14. 自动配置的数据Neo4j测试 
#### 43.3.15. 自动配置的数据Redis测试 
#### 43.3.16. 自动配置的数据LDAP测试 
#### 43.3.17. 自动配置的REST客户端 
#### 43.3.18. 自动配置的Spring REST Docs测试 自动配置的Spring REST Docs使用Mock MVC进行测试 自动配置的Spring REST Docs使用REST Assured进行测试 
#### 43.3.19. 用户配置和切片 
#### 43.3.20. 使用Spock测试Spring Boot应用程序 

### 43.4. 测试工具 
#### 43.4.1. ConfigFileApplicationContextInitializer 
#### 43.4.2. EnvironmentTestUtils 
#### 43.4.3. OutputCapture 
#### 43.4.4. TestRestTemplate

## 44. Web Sockets
## 45. Web Services

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

Spring Boot 2.0.0.RELEASE 需要：

1. Java 8 or Java 9
2. Spring Framework 5.0.4.RELEASE 或更高. 
3. Maven 3.2+ 和 Gradle 4.

### 9.1. Servlet 容器

Spring Boot 支持以下嵌入式 servlet 容器:

|名称	|Servlet 版本
|---|---
|Tomcat 8.5 |3.1
|Jetty 9.4 |3.1
|Undertow 1.4 |3.1

你也可以将 Spring Boot 应用部署到任何兼容 Servlet 3.0+ 的容器中。

## 10. Spring Boot 安装

Spring Boot可以与“classic”Java开发工具一起使用，也可以作为命令行工具安装。无论哪种方式，您都需要Java SDK v1.8或更高版本。在开始之前，您应该使用以下命令检查当前的Java安装：

```shell
$ java -version
```
如果您对Java开发不熟悉，或者想要试验Spring Boot，则可能需要先尝试Spring Boot CLI（命令行界面）。否则，请阅读“classic”安装说明。

### 10.1. Java 环境安装说明

您可以像使用任何标准Java库一样使用Spring Boot。为此，请在类路径中包含相应的`spring-boot-*.jar`文件。 Spring Boot不需要任何特殊的工具集成，因此您可以使用任何IDE或文本编辑器。此外，Spring Boot应用程序没有什么特别之处，因此您可以像运行其他任何Java程序一样运行和调试Spring Boot应用程序。

虽然您可以复制Spring Boot jar，但我们通常建议您使用支持依赖管理的构建工具（如Maven或Gradle）。

#### 10.1.1. Maven 安装

Spring Boot与Apache Maven 3.2或更高版本兼容。如果您尚未安装Maven，则可以按照maven.apache.org上的说明进行操作。

在许多操作系统上，Maven可以与包管理器一起安装。

如果您使用OSX Homebrew，请尝试 `brew install maven`。 

Ubuntu用户可以运行 `sudo apt-get install maven`。

具有Chocolatey的Windows用户可以在管理员权限提示符下运行 `choco install maven`。

Spring Boot依赖使用 `org.springframework.boot` `groupId`。通常，您的Maven POM文件继承自`spring-boot-starter-parent`项目并将依赖关系声明为一个或多个“Starter”。 Spring Boot还提供了一个可选的 Maven plugin 来创建可执行的jar。

以下列表显示了一个典型的pom.xml文件：

```xml
<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>

	<groupId>com.example</groupId>
	<artifactId>myproject</artifactId>
	<version>0.0.1-SNAPSHOT</version>

	<!-- Inherit defaults from Spring Boot -->
	<parent>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-parent</artifactId>
		<version>2.0.0.RELEASE</version>
	</parent>

	<!-- Add typical dependencies for a web application -->
	<dependencies>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-web</artifactId>
		</dependency>
	</dependencies>

	<!-- Package as an executable jar -->
	<build>
		<plugins>
			<plugin>
				<groupId>org.springframework.boot</groupId>
				<artifactId>spring-boot-maven-plugin</artifactId>
			</plugin>
		</plugins>
	</build>

</project>

```

`Spring-Boot-starter-parent` 是使用Spring Boot的好方法，但它可能并不适合所有的时间。有时您可能需要从不同的父POM继承，或者您可能不喜欢我们的默认设置。在这些情况下，请参见第13.2.2节“使用没有父POM的Spring Boot”，了解使用导入范围的替代解决方案。

#### 10.1.2. Gradle 安装

Spring Boot 与Gradle 4兼容。如果您尚未安装Gradle，可以按照 gradle.org/ 上的说明进行操作。

Spring Boot 依赖可以通过使用`org.springframework.boot` `group`声明。通常，您的项目将依赖项声明为一个或多个“Starter”。 Spring Boot提供了一个有用的 Gradle plugin，可以用来简化依赖声明和创建可执行的jar。

Gradle Wrapper 

当您需要构建项目时，Gradle Wrapper提供了一种“获取”Gradle的好方法。这是一个小脚本和库，与代码一起提交以引导构建过程。有关详细信息，请参阅

docs.gradle.org/4.2.1/userguide/gradle_wrapper.html。

以下示例显示了一个典型的build.gradle文件：

```java
plugins {
	id 'org.springframework.boot' version '2.0.0.RELEASE'
	id 'java'
}


jar {
	baseName = 'myproject'
	version =  '0.0.1-SNAPSHOT'
}

repositories {
	jcenter()
}

dependencies {
	compile("org.springframework.boot:spring-boot-starter-web")
	testCompile("org.springframework.boot:spring-boot-starter-test")
}
```

### 10.2. Spring Boot CLI 安装

Spring Boot CLI（Command Line Interface）是一个命令行工具，您可以使用它来快速使用Spring进行原型开发。它可以让你运行Groovy脚本，这意味着你有一个熟悉的类Java语法，没有太多的样板代码。 

您不需要使用CLI来使用Spring Boot，但它绝对是让Spring应用程序实现最快的最快捷方式。

#### 10.2.1. 手动安装

您可以从Spring软件存储库下载Spring CLI分发版：

* spring-boot-cli-2.0.0.RELEASE-bin.zip
* spring-boot-cli-2.0.0.RELEASE-bin.tar.gz

最先进的快照分布也可用。 

下载完成后，请按照解压缩归档中的 INSTALL.txt 说明进行操作。总之，在`.zip`文件的`bin/` 目录中有一个spring 脚本（用于Windows的`spring.bat`）。或者，您可以使用带有`.jar` 文件的 `java -jar`（该脚本可帮助您确定类路径设置正确）。

#### 10.2.2. SDKMAN 安装

SDKMAN!（The Software Development Kit Manager）可用于管理各种二进制SDK的多个版本，包括 Groovy 和 Spring Boot CLI。获取 SDKMAN！从 sdkman.io 安装并使用以下命令安装Spring Boot：

```
$ sdk install springboot
$ spring --version
Spring Boot v2.0.0.RELEASE
```
如果您为CLI开发功能并希望轻松访问您构建的版本，请使用以下命令：

```
$ sdk install springboot dev /path/to/spring-boot/spring-boot-cli/target/spring-boot-cli-2.0.0.RELEASE-bin/spring-2.0.0.RELEASE/
$ sdk default springboot dev
$ spring --version
Spring CLI v2.0.0.RELEASE
```
 
前面的指令安装一个称为`dev`实例的`spring`的本地实例。它指向您的目标构建位置，所以每次重建Spring Boot时，`spring`都是最新的。

您可以通过运行以下命令来查看它：

```
$ sdk ls springboot

================================================================================
Available Springboot Versions
================================================================================
> + dev
* 2.0.0.RELEASE

================================================================================
+ - local version
* - installed
> - currently in use
================================================================================
```

#### 10.2.3. OSX Homebrew 安装

如果您在Mac上并使用Homebrew，则可以使用以下命令安装Spring Boot CLI：

```
$ brew tap pivotal/tap
$ brew install springboot
```

Homebrew 安装 spring 到 /usr/local/bin 目录下。

> 如果您没有看到该项目，那么您的brew的安装可能会过时。在这种情况下，运行`brew update`并重试。

#### 10.2.4. MacPorts 安装

如果您在Mac上并使用MacPorts，则可以使用以下命令安装Spring Boot CLI：

```
$ sudo port install spring-boot-cli
```

#### 10.2.5. Command-line 工作

Spring Boot CLI包含为 BASH 和 zsh shell 提供命令完成的脚本。您可以在任何shell中将该脚本（也称为spring）源代码或将其放入个人或系统范围的bash完成初始化中。在Debian系统中，系统范围的脚本位于`/shell-completion/bash`中，并且在新shell启动时执行该目录中的所有脚本。

例如，要通过使用SDKMAN！安装，手动运行脚本，请使用以下命令：

```
$ . ~/.sdkman/candidates/springboot/current/shell-completion/bash/spring
$ spring <HIT TAB HERE>
  grab  help  jar  run  test  version
```

> 如果您使用Homebrew或MacPorts安装Spring Boot CLI，则命令行完成脚本会自动在您的shell中注册。

#### 10.2.6. Spring CLI 入门示例

您可以使用以下Web应用程序来测试您的安装。首先，创建一个名为`app.groovy`的文件，如下所示：

```
@RestController
class ThisWillActuallyRun {

	@RequestMapping("/")
	String home() {
		"Hello World!"
	}
}
```

然后从shell运行它，如下所示:

```
$ spring run app.groovy
```

在网页浏览器中打开 localhost:8080。您应该看到以下输出：

```
Hello World!
```

### 10.3. Spring Boot 旧版本升级

如果您是从早期版本的Spring Boot进行升级，请查看项目wiki上的“迁移指南”，其中提供了详细的升级说明。还要检查“发行说明”，以获取每个发行版的“新功能”和“值得注意”功能列表。

要升级现有的CLI安装，请使用相应的软件包管理器命令（例如，`brew upgrade`），或者如果您手动安装了CLI，请遵循标准说明，记住更新`PATH`环境变量以删除所有旧的引用。

## 11. 开发你的第一个 Spring Boot 应用

本节介绍如何开发一个简单的“Hello World！”Web应用程序，该应用程序重点介绍Spring Boot的一些主要功能。

我们使用Maven来构建这个项目，因为大多数IDE都支持它。

在开始之前，请打开终端并运行以下命令以确保您已安装了Java和Maven的有效版本：

```
$ java -version
java version "1.8.0_102"
Java(TM) SE Runtime Environment (build 1.8.0_102-b14)
Java HotSpot(TM) 64-Bit Server VM (build 25.102-b14, mixed mode)
```

```
$ mvn -v
Apache Maven 3.3.9 (bb52d8502b132ec0a5a3f4c09453c07478323dc5; 2015-11-10T16:41:47+00:00)
Maven home: /usr/local/Cellar/maven/3.3.9/libexec
Java version: 1.8.0_102, vendor: Oracle Corporation
```

此示例需要在其自己的文件夹中创建。后续说明假定您已经创建了合适的文件夹，并且它是您当前的目录。

### 11.1. 创建 POM

我们需要从创建一个Maven pom.xml文件开始。 pom.xml是用于构建项目的配方。

打开您最喜欢的文本编辑器并添加以下内容：

```xml
<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>

	<groupId>com.example</groupId>
	<artifactId>myproject</artifactId>
	<version>0.0.1-SNAPSHOT</version>

	<parent>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-parent</artifactId>
		<version>2.0.0.RELEASE</version>
	</parent>

	<!-- Additional lines to be added here... -->

</project>
```

前面的列表应该给你一个工作版本。您可以通过运行mvn包来测试它（现在，您可以忽略“jar将为空 - 没有内容被标记为包含！”警告）。


>此时，您可以将项目导入IDE（大多数现代Java IDE包含对Maven的内置支持）。为了简单起见，我们在本例中继续使用纯文本编辑器。

### 11.2. 添加类路径依赖关系

Spring Boot提供了许多“Starters”，这可让您将jar添加到类路径中。我们的示例应用程序已经在POM的父节点中使用了`spring-boot-starter-parent`。 `spring-boot-starter-parent`是一个特别的启动器，它提供了有用的Maven默认值。它还提供了一个`dependency-management` 部分，以便您可以省略“version”依赖项的版本标签。

其他“Starters”提供了在开发特定类型的应用程序时可能需要的依赖关系。由于我们正在开发一个Web应用程序，因此我们添加了`spring-boot-starter-web`依赖项。在此之前，我们可以通过运行以下命令来查看我们目前的功能：

```
$ mvn dependency:tree

[INFO] com.example:myproject:jar:0.0.1-SNAPSHOT
``

`mvn dependency:tree` 命令打印项目依赖关系的树形表示。你可以看到`spring-boot-starter-parent`本身不提供依赖关系。要添加必要的依赖关系，请编辑您的pom.xml并在父节点下方添加`spring-boot-starter-web`依赖项：

```xml
<dependencies>
	<dependency>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-web</artifactId>
	</dependency>
</dependencies>
```

如果您再次运行 `mvn dependency：tree`，则会发现现在还有许多其他依赖项，包括Tomcat Web服务器和Spring Boot本身。


### 11.3. 编写代码

为了完成我们的应用程序，我们需要创建一个Java文件。默认情况下，Maven会从 `src/main/java` 编译源代码，因此您需要创建该文件夹结构，然后添加名为 `src/main/java/Example.java` 的文件以包含以下代码：

```java
import org.springframework.boot.*;
import org.springframework.boot.autoconfigure.*;
import org.springframework.web.bind.annotation.*;

@RestController
@EnableAutoConfiguration
public class Example {

	@RequestMapping("/")
	String home() {
		return "Hello World!";
	}

	public static void main(String[] args) throws Exception {
		SpringApplication.run(Example.class, args);
	}

}
```

虽然这里没有太多的代码，但还是有很多。我们将在接下来的几节中介绍一些重要的部分。

#### 11.3.1. @RestController 和 @RequestMapping 注解

我们的`Example`类的第一个注释是`@RestController`。这被称为刻板印记。它为阅读代码的人提供了线索，对于Spring来说，这个类扮演着特定的角色。在这种情况下，我们的类是一个web `@Controller`，所以Spring在处理传入的Web请求时会考虑它。 

`@RequestMapping`注释提供了“routing”信息。它告诉Spring，任何带有`/` 路径的HTTP请求都应该映射到`home`方法。 `@RestController`注释告诉Spring将结果字符串直接呈现给调用者。

> `@RestController` 和 `@RequestMapping` 注解是Spring MVC注释。 （它们并不特定于Spring Boot。）有关更多详细信息，请参阅Spring参考手册中的MVC部分。

#### 11.3.2. @EnableAutoConfiguration 注解

第二个类级注释是 `@EnableAutoConfiguration`。这个注解告诉Spring Boot根据你添加的jar依赖来“猜测”你想要如何配置Spring。由于 `spring-boot-starter-web` 添加了Tomcat和Spring MVC，因此自动配置假定您正在开发Web应用程序并相应地设置Spring。

```
启动器和自动配置

自动配置旨在与“Starter”配合使用，但这两个概念并不直接相关。您可以自由选择初学者之外的jar依赖项。 Spring Boot仍然尽力自动配置您的应用程序。
```

#### 11.3.3. “main” 方法

我们应用程序的最后一部分是 `main` 方法。这只是遵循Java约定的应用程序入口点的标准方法。我们的主要方法通过调用 `run` 来委托 `Spring Boot` 的 `SpringApplication` 类。 SpringApplication启动我们的应用程序，从Spring开始，然后启动自动配置的Tomcat Web服务器。我们需要将 `Example.class` 作为参数传递给run方法，以告知`SpringApplication` 是Spring的主要组件。 args数组也被传递以暴露任何命令行参数。

### 11.4. 运行示例

这时，你的应用程序应该工作。由于您使用了 `spring-boot-starter-parent` POM，因此您可以使用有用的`run`目标来启动应用程序。键入 `mvn spring-boot:run` 从根项目目录运行以启动应用程序。您应该看到类似于以下内容的输出：

```
$ mvn spring-boot:run

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::  (v2.0.0.RELEASE)
....... . . .
....... . . . (log output here)
....... . . .
........ Started Example in 2.222 seconds (JVM running for 6.514)
```

如果您打开一个Web浏览器到 `http://localhost:8080` ，您应该看到以下输出：

```
Hello World!
```

要正常退出应用程序，请按 ctrl-c。

### 11.5. 创建可执行 Jar 包

我们通过创建一个完全独立的可执行jar文件来完成我们的示例，该文件可以在生产环境中运行。可执行jar（有时称为“fat jars”）是包含您的编译类以及您的代码需要运行的所有jar依赖项的归档文件。

可执行的 jars 和 Java 

Java没有提供加载嵌套jar文件的标准方式（本身包含在jar中的jar文件）。如果您想分发自包含的应用程序，这可能会有问题。 

为了解决这个问题，许多开发者使用 “uber” jars。一个超级jar将所有应用程序依赖关系中的所有类打包到一个单独的存档中。这种方法的问题是很难看到你的应用程序中有哪些库。如果在多个 jar 中使用相同的文件名（但是具有不同的内容），则它也可能是有问题的。 

Spring Boot 采用了不同的方法，可以让您直接嵌入 jars。

要创建一个可执行的 jar，我们需要将 `spring-boot-maven-plugin` 添加到我们的pom.xml中。为此，请在依赖性部分的下面插入以下几行：

```xml
<build>
	<plugins>
		<plugin>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-maven-plugin</artifactId>
		</plugin>
	</plugins>
</build>
```

`spring-boot-starter-parent` POM包含 `<executions>` 配置来绑定重新打包目标。如果您不使用父POM，则需要自行声明此配置。有关详细信息，请参阅插件文档。

保存你的pom.xml并从命令行运行mvn包，如下所示：

```
$ mvn package

[INFO] Scanning for projects...
[INFO]
[INFO] ------------------------------------------------------------------------
[INFO] Building myproject 0.0.1-SNAPSHOT
[INFO] ------------------------------------------------------------------------
[INFO] .... ..
[INFO] --- maven-jar-plugin:2.4:jar (default-jar) @ myproject ---
[INFO] Building jar: /Users/developer/example/spring-boot-example/target/myproject-0.0.1-SNAPSHOT.jar
[INFO]
[INFO] --- spring-boot-maven-plugin:2.0.0.RELEASE:repackage (default) @ myproject ---
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
```

如果您查看目标目录，则应该看到 `myproject-0.0.1-SNAPSHOT.jar`。该文件的大小应该在10 MB左右。

如果你想在里面偷看，你可以使用 `java -jar`，如下所示：

```
$ jar tvf target/myproject-0.0.1-SNAPSHOT.jar
```

您还应该在目标目录中看到名为 `myproject-0.0.1-SNAPSHOT.jar.original` 的小得多的文件。这是Maven在被`Spring Boot`重新包装之前创建的原始jar文件。

要运行该应用程序，请使用`java -jar`命令，如下所示：

```
$ java -jar target/myproject-0.0.1-SNAPSHOT.jar

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::  (v2.0.0.RELEASE)
....... . . .
....... . . . (log output here)
....... . . .
........ Started Example in 2.536 seconds (JVM running for 2.864)
```

和以前一样，要退出应用程序，请按ctrl-c。

## 12. 接下来要阅读的内容

希望本节提供了一些Spring Boot的基础知识，并帮助您编写自己的应用程序。如果您是面向任务的开发人员，则可能需要跳至spring.io，查看一些入门指南，以解决具体的“我该如何使用Spring？”问题。我们也有Spring Boot专用的“How-to”参考文档。

Spring Boot存储库还有一堆你可以运行的样本。样本与代码的其余部分无关（也就是说，您不需要构建其余代码以运行或使用样本）。

否则，下一个逻辑步骤是阅读第三部分“使用Spring Boot”。如果你真的不耐烦，你也可以跳到前面阅读Spring Boot的功能。


# III. 使用 Spring Boot

本节将详细介绍如何使用Spring Boot。它涵盖了构建系统，自动配置以及如何运行应用程序等主题。我们还介绍了一些Spring Boot的最佳实践。尽管Spring Boot没有特别的特殊之处（它只是您可以使用的另一个库），但有一些建议，如果遵循这些建议，您的开发过程会更容易一些。

如果您刚开始使用Spring Boot，那么在深入本节之前，您应该阅读入门指南。

## 13. 构建

强烈建议您选择支持依赖关系管理的构建系统，并且可以使用发布到“Maven Central”存储库的构件。我们建议您选择 Maven 或 Gradle。 Spring Boot可以与其他构建系统（例如Ant）一起工作，但它们并没有得到特别好的支持。


### 13.1. 依赖管理

Spring Boot的每个发行版都提供了它支持的依赖关系的策略列表。实际上，您不需要为构建配置中的任何这些依赖项提供版本，因为Spring Boot为您管理这些版本。当您升级Spring Boot本身时，这些依赖关系也会以一致的方式升级。

> 如果需要的话，你仍然可以指定一个版本并覆盖Spring Boot的建议。

策划列表包含您可以在 Spring Boot 中使用的所有 Spring 模块以及第三方库的精炼列表。该列表可用作 Bills of Materials（spring-boot-dependencies），可用于 Maven 和Gradle。

> Spring Boot 的每个版本都与 Spring Framework 的基本版本相关联。我们强烈建议您不要指定其版本。

### 13.2. Maven

Maven用户可以继承 `spring-boot-starter-parent` 项目以获得合理的默认值。父项目提供以下功能：

* Java 1.8作为默认的编译器级别。
* UTF-8源码编码。
* 依赖管理部分，继承自spring-boot-dependencies pom，用于管理公共依赖的版本。这种依赖关系管理可以让您在自己的pom中使用这些依赖项时忽略<version>标记。
* 智能的资源过滤。
* 智能的插件配置（exec 插件，Git commit ID 和 shade）。
* 对 `application.properties` 和 `application.yml` 进行智能的资源过滤，包括特定于配置文件的文件（例如，`application-dev.properties` 和 `application-dev.yml`）

请注意，由于 `application.properties` 和 `application.yml` 文件接受Spring样式占位符（`$ {...}`），因此Maven过滤将更改为使用 `@..@` 占位符。 （您可以通过设置名为`resource.delimiter`的 Maven属性来覆盖该属性。）

#### 13.2.1. 继承 Starter Parent

要将项目配置为从`spring-boot-starter-parent`继承，请按如下所示设置父项：

```xml
<!-- Inherit defaults from Spring Boot -->
<parent>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-parent</artifactId>
	<version>2.0.0.RELEASE</version>
</parent>
```

> 您应该只需在此依赖项上指定Spring Boot版本号。如果您导入其他启动器，则可以安全地省略版本号。

通过该设置，您还可以通过覆盖自己项目中的属性来覆盖各个依赖项。例如，要升级到另一个`Spring Data`发行版，您可以将以下内容添加到您的pom.xml中：

```xml
<properties>
	<spring-data-releasetrain.version>Fowler-SR2</spring-data-releasetrain.version>
</properties>

```

> 检查`spring-boot-dependencies` pom以获取支持的属性列表。

#### 13.2.2. 使用 Spring Boot 不依赖父 POM

不是每个人都喜欢从`spring-boot-starter-parent` POM继承。您可能拥有自己的公司标准父项，或者您可能更愿意明确声明所有Maven配置

如果你不想使用`spring-boot-starter-parent`，你仍然可以通过使用`scope = import` dependency来保持依赖管理的好处（但不是插件管理），如下所示：

```xml
<dependencyManagement>
	<dependencies>
		<dependency>
			<!-- Import dependency management from Spring Boot -->
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-dependencies</artifactId>
			<version>2.0.0.RELEASE</version>
			<type>pom</type>
			<scope>import</scope>
		</dependency>
	</dependencies>
</dependencyManagement>
```

如上所述，上述示例设置不会让您使用属性重写个别依赖关系。要达到相同的结果，需要在`spring-boot-dependencies`条目之前在项目的`dependencyManagement`中添加一个条目。例如，要升级到另一个Spring Data发行版，您可以将以下元素添加到您的pom.xml中：

```xml
<dependencyManagement>
	<dependencies>
		<!-- Override Spring Data release train provided by Spring Boot -->
		<dependency>
			<groupId>org.springframework.data</groupId>
			<artifactId>spring-data-releasetrain</artifactId>
			<version>Fowler-SR2</version>
			<type>pom</type>
			<scope>import</scope>
		</dependency>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-dependencies</artifactId>
			<version>2.0.0.RELEASE</version>
			<type>pom</type>
			<scope>import</scope>
		</dependency>
	</dependencies>
</dependencyManagement>
```

> 在前面的例子中，我们指定了一个BOM，但是任何依赖类型都可以用相同的方式覆盖。

#### 13.2.3. 使用 Spring Boot Maven 插件

Spring Boot 包含一个Maven插件，可以将项目打包为可执行的jar。如果要使用插件，请将插件添加到`<plugins>`部分，如以下示例所示：

```xml
<build>
	<plugins>
		<plugin>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-maven-plugin</artifactId>
		</plugin>
	</plugins>
</build>

```

> 如果您使用Spring Boot启动器父POM，则只需添加插件。除非您想更改父级中定义的设置，否则无需对其进行配置。

### 13.3. Gradle

要了解如何使用Spring Boot和Gradle，请参阅Spring Boot的Gradle插件的文档：

* 参考 (HTML and PDF)
* API

### 13.4. Ant

可以使用Apache Ant + Ivy构建Spring Boot项目。 `spring-boot-antlib` “AntLib”模块也可以帮助Ant创建可执行的jar文件。 为了声明依赖关系，典型的`ivy.xml`文件看起来像下面的例子：

```xml
<ivy-module version="2.0">
	<info organisation="org.springframework.boot" module="spring-boot-sample-ant" />
	<configurations>
		<conf name="compile" description="everything needed to compile this module" />
		<conf name="runtime" extends="compile" description="everything needed to run this module" />
	</configurations>
	<dependencies>
		<dependency org="org.springframework.boot" name="spring-boot-starter"
			rev="${spring-boot.version}" conf="compile" />
	</dependencies>
</ivy-module>
```

典型的build.xml如下例所示：

```xml
<project
	xmlns:ivy="antlib:org.apache.ivy.ant"
	xmlns:spring-boot="antlib:org.springframework.boot.ant"
	name="myapp" default="build">

	<property name="spring-boot.version" value="2.0.0.RELEASE" />

	<target name="resolve" description="--> retrieve dependencies with ivy">
		<ivy:retrieve pattern="lib/[conf]/[artifact]-[type]-[revision].[ext]" />
	</target>

	<target name="classpaths" depends="resolve">
		<path id="compile.classpath">
			<fileset dir="lib/compile" includes="*.jar" />
		</path>
	</target>

	<target name="init" depends="classpaths">
		<mkdir dir="build/classes" />
	</target>

	<target name="compile" depends="init" description="compile">
		<javac srcdir="src/main/java" destdir="build/classes" classpathref="compile.classpath" />
	</target>

	<target name="build" depends="compile">
		<spring-boot:exejar destfile="build/myapp.jar" classes="build/classes">
			<spring-boot:lib>
				<fileset dir="lib/runtime" />
			</spring-boot:lib>
		</spring-boot:exejar>
	</target>
</project>

```

> 如果您不想使用 `spring-boot-antlib`模块，请参见第86.9节 “在不使用`spring-boot-antlib`的情况下从Ant生成可执行文件”“操作方法”

### 13.5. Starters

启动器是一套方便的依赖描述符，可以包含在应用程序中。您可以获得所需的所有Spring及相关技术的一站式商店，而无需查看示例代码并复制粘贴依赖描述符。例如，如果您想开始使用Spring和JPA进行数据库访问，请在项目中包含 `spring-boot-starter-data-jpa` 依赖项。

starters 包含很多依赖项，您需要快速启动并快速运行项目，并且需要一组支持的可传递依赖关系。

> 怎么命名？
> 
> 所有官方首发者都遵循类似的命名模式; `spring-boot-starter-*`，其中`*`是特定类型的应用程序。这种命名结构旨在帮助您在需要查找启动器时。许多IDE中的Maven集成允许您按名称搜索依赖项。例如，通过安装适当的Eclipse或STS插件，您可以在POM编辑器中按`ctrl-space`并键入`spring-boot-starter`获取完整列表。
> 
> 正如“创建自己的启动器”部分所述，第三方启动器不应该从启动引导开始，因为它是为官方Spring Boot工件保留的。相反，第三方初学者通常以项目名称开头。例如，名为thirdpartyproject的第三方启动器项目通常会被命名为thirdpartyproject-spring-boot-starter。

以下应用程序 starters 由 Spring Boot 在`org.springframework.boot`组下提供：

Spring Boot application starters

|名字|描述|Pom
|---|---|---
|spring-boot-starter|核心启动，包含自动配置支持，logging and YAML|Pom
|spring-boot-starter-activemq|以JMS方式使用 Apache ActiveMQ|Pom
|spring-boot-starter-amqp|使用 Spring AMQP and Rabbit MQ|Pom
|spring-boot-starter-aop|使用Spring AOP and AspectJ 面向切面编程|Pom
|spring-boot-starter-artemis|以JMS方式使用 Apache Artemis|Pom
|spring-boot-starter-batch|使用 Spring Batch|Pom
|spring-boot-starter-cache|使用 Spring Framework’s caching|Pom
|spring-boot-starter-cloud-connectors|使用 Spring Cloud Connectors|Pom
|spring-boot-starter-data-cassandra|使用 Spring Data Cassandra|Pom
|spring-boot-starter-data-cassandra-reactive|使用响应式 Spring Data Cassandra|Pom
|spring-boot-starter-data-couchbase|使用 Spring Data Couchbase |Pom
|spring-boot-starter-data-couchbase-reactive|使用响应式 Spring Data Couchbase |Pom
|spring-boot-starter-data-elasticsearch|使用 Spring Data Elasticsearch|Pom
|spring-boot-starter-data-jpa|使用 Spring Data JPA with Hibernate|Pom
|spring-boot-starter-data-ldap|使用 Spring Data LDAP|Pom
|spring-boot-starter-data-mongodb|使用 Spring Data MongoDB |Pom
|spring-boot-starter-data-mongodb-reactive|使用响应式 Spring Data MongoDB |Pom
|spring-boot-starter-data-neo4j|使用 Spring Data Neo4j|Pom
|spring-boot-starter-data-redis|使用 Spring Data Redis|Pom
|spring-boot-starter-data-redis-reactive|使用响应式 Spring Data Redis|Pom
|spring-boot-starter-data-rest|使用 Spring Data REST|Pom
|spring-boot-starter-data-solr|使用 Apache Solr 搜索|Pom
|spring-boot-starter-freemarker|使用 FreeMarker 模板做视图层|Pom
|spring-boot-starter-groovy-templates|使用 Groovy 模板做视图层|Pom
|spring-boot-starter-hateoas|使用 Spring MVC 和 Spring HATEOAS|Pom
|spring-boot-starter-integration |使用 Spring Integration|Pom
|spring-boot-starter-jdbc |使用 Tomcat JDBC 连接池|Pom
|spring-boot-starter-jersey |使用 JAX-RS 和 Jersey|Pom
|spring-boot-starter-jooq |使用 jOOQ 访问 SQL 数据库|Pom
|spring-boot-starter-json |读写json|Pom
|spring-boot-starter-jta-atomikos |使用 Atomikos 做 JTA|Pom
|spring-boot-starter-jta-bitronix |使用 Bitronix 做 JTA|Pom
|spring-boot-starter-jta-narayana |使用 Spring Boot Narayana JTA|Pom
|spring-boot-starter-mail |使用 Java Mail 和 Spring Framework’s email|Pom
|spring-boot-starter-mustache |使用 Mustache 做视图层|Pom
|spring-boot-starter-quartz |使用 Spring Boot Quartz|Pom
|spring-boot-starter-security |使用 Spring Security|Pom
|spring-boot-starter-test |使用 JUnit, Hamcrest and Mockito 做测试|Pom
|spring-boot-starter-thymeleaf |使用 Thymeleaf 做视图层|Pom
|spring-boot-starter-validation |使用 Java Bean Validation with Hibernate Validator|Pom
|spring-boot-starter-web |使用 Spring MVC|Pom
|spring-boot-starter-web-services |使用 Spring Web Services|Pom
|spring-boot-starter-webflux |构建 WebFlux 应用|Pom
|spring-boot-starter-websocket |构建 WebSocket 应用|Pom

除应用程序启动器外，还可以使用以下启动器来添加生产准备功能：

Spring Boot production starters

|名字|描述|Pom
|---|---|---
|spring-boot-starter-actuator|帮助监控生产服务器的健康状况|Pom


最后，Spring Boot还包含以下启动器，如果您想要排除或交换特定技术方面，可以使用以下启动器：

|名字|描述|Pom
|---|---|---
|spring-boot-starter-jetty|Jetty容器|Pom
|spring-boot-starter-log4j2|log4j2日志系统|Pom
|spring-boot-starter-logging|logging日志系统|Pom
|spring-boot-starter-reactor-netty|响应式netty容器|Pom
|spring-boot-starter-tomcat|Tomcat容器|Pom
|spring-boot-starter-undertow|Undertow容器|Pom


## 14. 组织你的代码

Spring Boot不需要任何特定的代码布局来工作。但是，有一些最佳实践可以提供帮助。



### 14.1. 使用“默认”包

当一个类不包含包声明时，它被认为是在“默认包”中。通常不鼓励使用“默认包”，应该避免使用。对于使用`@ComponentScan`，`@EntityScan`或`@SpringBootApplication`批注的Spring Boot应用程序，它可能会导致特定问题，因为每个jar的每个类都被读取。

> 我们建议您遵循Java推荐的软件包命名约定并使用反向域名（例如，com.example.project）。

### 14.2. 查找主要应用程序类

我们通常建议您将主应用程序类定位在其他类上方的根包中。 `@EnableAutoConfiguration` 注释通常放在您的主类上，它隐式地为特定项目定义了一个基本“搜索包”。例如，如果您正在编写JPA应用程序，则使用`@EnableAutoConfiguration`注释类的包来搜索`@Entity`项目。

使用根包也可以使用`@ComponentScan`注释而无需指定`basePackage`属性。如果您的主类位于根包中，您还可以使用`@SpringBootApplication`注释。

下面的清单显示了一个典型的布局：

```
com
 +- example
     +- myapplication
         +- Application.java
         |
         +- customer
         |   +- Customer.java
         |   +- CustomerController.java
         |   +- CustomerService.java
         |   +- CustomerRepository.java
         |
         +- order
             +- Order.java
             +- OrderController.java
             +- OrderService.java
             +- OrderRepository.java
```

Application.java文件将声明主要方法以及基本的@Configuration，如下所示：

```java
package com.example.myapplication;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.EnableAutoConfiguration;
import org.springframework.context.annotation.ComponentScan;
import org.springframework.context.annotation.Configuration;

@Configuration
@EnableAutoConfiguration
@ComponentScan
public class Application {

	public static void main(String[] args) {
		SpringApplication.run(Application.class, args);
	}

}
```

## 15. 配置类

Spring Boot 支持基于Java的配置。虽然可以将`SpringApplication`与XML源一起使用，但我们通常建议您的主源是一个`@Configuration`类。通常，定义主要方法的类作为主要`@Configuration`是一个很好的候选者。

> 许多使用XML配置的互联网上发布了Spring配置示例。如果可能，请始终尝试使用等效的基于Java的配置。搜索启用*注释可能是一个很好的起点。



### 15.1. 导入其他配置类

你不需要把你所有的`@Configuration`放到一个类中。 `@Import`注释可用于导入其他配置类。或者，您可以使用`@ComponentScan`自动获取所有Spring组件，包括`@Configuration`类。

### 15.2. 导入 XML 配置

如果您必须使用基于XML的配置，我们建议您仍以`@Configuration`类开头。然后您可以使用`@ImportResource`注释来加载XML配置文件。

## 16. Auto-configuration

Spring Boot自动配置会尝试根据您添加的jar依赖关系自动配置您的Spring应用程序。例如，如果HSQLDB在您的类路径中，并且您尚未手动配置任何数据库连接Bean，则Spring Boot会自动配置内存数据库。

您需要选择加入自动配置，方法是将`@EnableAutoConfiguration`或`@SpringBootApplication`注释添加到其中一个`@Configuration`类中。

> 您应该只添加一个`@EnableAutoConfiguration`注释。我们通常建议您将它添加到您的主要`@Configuration`类中。


### 16.1. 逐渐替换 Auto-configuration

自动配置是非侵入式的。在任何时候，您都可以开始定义自己的配置以替换自动配置的特定部分。例如，如果您添加自己的DataSource Bean，则默认的嵌入式数据库支持会被取消。 

如果您需要了解当前正在应用的自动配置以及为什么使用--debug开关启动应用程序。这样做可以为选定的核心记录器启用调试日志，并将条件报告记录到控制台。

### 16.2. 禁用特定的 Auto-configuration 类

如果您发现不需要的特定自动配置类正在应用，则可以使用@EnableAutoConfiguration的exclude属性来禁用它们，如以下示例所示：

```java
import org.springframework.boot.autoconfigure.*;
import org.springframework.boot.autoconfigure.jdbc.*;
import org.springframework.context.annotation.*;

@Configuration
@EnableAutoConfiguration(exclude={DataSourceAutoConfiguration.class})
public class MyConfiguration {

}
```

如果该类不在类路径中，则可以使用注释的`excludeName`属性并改为指定完全限定名称。最后，您还可以通过使用`spring.autoconfigure.exclude`属性来控制要排除的自动配置类的列表。

>您可以通过注释级别和使用属性来定义排除。

## 17. Spring Beans 和依赖注入

您可以自由使用任何标准的Spring框架技术来定义您的bean及其注入的依赖关系。为了简单起见，我们经常发现使用`@ComponentScan`（查找bean）和使用`@Autowired`（执行构造函数注入）效果很好。

如果按照上面的建议构建代码（将您的应用程序类定位到根包中），则可以添加`@ComponentScan`而不带任何参数。所有的应用程序组件（`@Component`，`@Service`，`@Repository`，`@Controller`等）都会自动注册为Spring Bean。

以下示例显示了一个`@Service` Bean，它使用构造函数注入来获取必需的RiskAssessor bean：

```java

package com.example.service;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Service;

@Service
public class DatabaseAccountService implements AccountService {

	private final RiskAssessor riskAssessor;

	@Autowired
	public DatabaseAccountService(RiskAssessor riskAssessor) {
		this.riskAssessor = riskAssessor;
	}

	// ...

}
```

如果一个bean有一个构造函数，那么可以省略@Autowired，如下例所示：

```
@Service
public class DatabaseAccountService implements AccountService {

	private final RiskAssessor riskAssessor;

	public DatabaseAccountService(RiskAssessor riskAssessor) {
		this.riskAssessor = riskAssessor;
	}

	// ...

}
```

> 注意如何使用构造函数注入让riskAssessor字段被标记为final，表明它不能被随后改变。

## 18. 使用 @SpringBootApplication 注解

许多Spring Boot开发人员总是使用`@Configuration`，`@EnableAutoConfiguration`和`@ComponentScan`注解其主类。由于这些注释经常一起使用（特别是如果您遵循上述最佳实践），Spring Boot提供了一种方便的`@SpringBootApplication`替代方法。

`@SpringBootApplication`注释等价于使用`@Configuration`，`@EnableAutoConfiguration`和`@ComponentScan`及其默认属性，如以下示例所示：


```java

package com.example.myapplication;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

@SpringBootApplication // same as @Configuration @EnableAutoConfiguration @ComponentScan
public class Application {

	public static void main(String[] args) {
		SpringApplication.run(Application.class, args);
	}

}
```

> `@SpringBootApplication`还提供别名来自定义`@EnableAutoConfiguration`和`@ComponentScan`的属性。


## 19. 运行你的应用

将应用程序打包为jar并使用嵌入式HTTP服务器的最大优点之一是，您可以像运行其他应用程序一样运行应用程序。调试Spring Boot应用程序也很容易。您不需要任何特殊的IDE插件或扩展。

> 本节仅涵盖基于jar的包装。如果您选择将应用程序打包为war文件，则应参考您的服务器和IDE文档。


### 19.1. 使用 IDE 运行

您可以从IDE运行Spring Boot应用程序作为简单的Java应用程序。但是，您首先需要导入您的项目。导入步骤取决于您的IDE和构建系统。大多数IDE可以直接导入Maven项目。例如，Eclipse用户可以从 File 菜单中选择 `Import ...→Existing Maven Projects`。

如果您无法直接将您的项目导入IDE，则可以使用构建插件生成IDE元数据。 Maven包含Eclipse和IDEA的插件。 Gradle为各种IDE提供插件。

> 如果您意外运行了两次Web应用程序，则会看到“端口已被使用”错误。 STS用户可以使用`Relaunch`按钮而不是运行按钮来确保关闭任何现有的实例。


### 19.2. 运行打包应用

如果使用Spring Boot Maven或Gradle插件创建可执行jar，则可以使用`java -jar`运行应用程序，如以下示例所示：

```
$ java -jar target/myapplication-0.0.1-SNAPSHOT.jar
```

也可以在启用远程调试支持的情况下运行打包的应用程序。这样做可以让您将调试器附加到打包的应用程序，如以下示例所示：

```
$ java -Xdebug -Xrunjdwp:server=y,transport=dt_socket,address=8000,suspend=n \
       -jar target/myapplication-0.0.1-SNAPSHOT.jar
```

### 19.3. 使用 Maven 插件

Spring Boot Maven插件包含一个可用于快速编译和运行应用程序的运行目标。应用程序以分解形式运行，就像它们在IDE中一样。以下示例显示了运行Spring Boot应用程序的典型Maven命令：

```
$ mvn spring-boot:run
```
您可能还想使用`MAVEN_OPTS`操作系统环境变量，如下例所示：

```
$ export MAVEN_OPTS=-Xmx1024m
```

### 19.4. 使用 Gradle 插件

Spring Boot Gradle插件还包含一个bootRun任务，可用于以分解形式运行您的应用程序。每当您应用org.springframework.boot和java插件并在以下示例中显示时，都会添加bootRun任务：

```
$ gradle bootRun
```

您可能还想使用`JAVA_OPTS`操作系统环境变量，如以下示例所示：

```
$ export MAVEN_OPTS=-Xmx1024m

```

### 19.5. 热交换

由于Spring Boot应用程序只是普通的Java应用程序，所以JVM热插拔应该可以开箱即用。 JVM热插拔在可以替换的字节码方面有所限制。对于更完整的解决方案，可以使用JRebel。

`spring-boot-devtools`模块还包含对快速重新启动应用程序的支持。

有关详细信息，请参阅本章后面的第20章开发人员工具部分以及热插拔“操作方法”。

## 20. 开发工具

Spring Boot包含一组额外的工具，可以使应用程序开发体验更愉快。 `spring-boot-devtools`模块可以包含在任何项目中以提供额外的开发时间功能。要包含devtools支持，请将模块依赖项添加到您的构建中，如Maven和Gradle的以下列表所示：

Maven:

```xml
<dependencies>
	<dependency>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-devtools</artifactId>
		<optional>true</optional>
	</dependency>
</dependencies>
```

```gradle
dependencies {
	compile("org.springframework.boot:spring-boot-devtools")
}
```

>运行完整打包的应用程序时，开发人员工具会自动禁用如果您的应用程序是从`java -jar`启动的，或者如果它是从特殊的类加载器启动的，那么它被认为是“生产应用程序”。将依赖标记为`optional`是一种最佳实践，可防止devtools被传递应用到其他使用您项目的模块。 Gradle不支持可选的依赖关系，因此您可能需要查看propdeps插件。
>
>重新打包的档案在默认情况下不包含devtools。如果您想使用某个远程devtools功能，则需要禁用excludeDevtools生成属性以包含它。该属性支持Maven和Gradle插件。

### 20.1. 属性默认值

`Spring Boot`支持的一些库使用缓存来提高性能。例如，`template engines`缓存已编译的模板以避免重复解析模板文件。另外，`Spring MVC`可以在服务静态资源时将HTTP缓存头添加到响应中。

虽然缓存在生产中非常有用，但它在开发过程中会起到反作用，使您无法看到您在应用程序中所做的更改。因此，`spring-boot-devtools`默认禁用缓存选项。

缓存选项通常由您的`application.properties`文件中的设置进行配置。例如，Thymeleaf提供了`spring.thymeleaf.cache`属性。而不是需要手动设置这些属性，`spring-boot-devtools`模块会自动应用合理的开发时配置。

> 有关devtools应用的属性的完整列表，请参阅DevToolsPropertyDefaultsPostProcessor。


### 20.2. 自动重启

每当类路径上的文件发生更改时，使用`spring-boot-devtools`的应用程序都会自动重新启动。在IDE中工作时，这可能是一个有用的功能，因为它为代码更改提供了非常快速的反馈循环。默认情况下，监视指向文件夹的类路径上的任何条目以进行更改。请注意，某些资源（如静态资产和视图模板）不需要重新启动应用程序。

触发重启

由于DevTools监控类路径资源，触发重启的唯一方法是更新类路径。导致类路径更新的方式取决于您使用的IDE。在Eclipse中，保存修改后的文件会导致更新类路径并触发重新启动。在IntelliJ IDEA中，构建项目（`Build - > Make Project`）具有相同的效果。

> 只要启用forking，您也可以使用受支持的构建插件（Maven和Gradle）启动您的应用程序，因为DevTools需要隔离的应用程序类加载器才能正常运行。默认情况下，当他们在类路径中检测到DevTools时，Gradle和Maven会这样做。

> 与LiveReload一起使用时，自动重启的效果非常好。有关详细信息，请参阅LiveReload部分。如果使用JRebel，则禁用自动重新启动，以支持动态类重新加载。其他devtools功能（例如LiveReload和属性覆盖）仍然可以使用。

> DevTools依靠应用程序上下文的关闭挂钩在重新启动期间关闭它。如果您禁用了关闭挂钩（`SpringApplication.setRegisterShutdownHook（false）`），它将无法正常工作。

> 在决定类路径中的条目是否会在更改时触发重新启动时，DevTools会自动忽略名为`spring-boot`，`spring-boot-devtools`，`spring-boot-autoconfigure`，`spring-boot-actuator`和`spring-boot-starter`的项目。

> DevTools需要自定义`ApplicationContext`使用的`ResourceLoader`。如果你的应用程序已经提供了一个，它将被包装。不支持直接覆盖`ApplicationContext` 上的 `getResource`方法。

>Restart vs Reload
>
>Spring Boot提供的重启技术通过使用两个类加载器来工作。不改变的类（例如来自第三方jar的类）被加载到基类加载器中。您正在开发的类会加载到重启类加载器中。当应用程序重新启动时，重新启动类加载器将被丢弃并创建一个新类。这种方法意味着应用程序重启通常比“冷启动”快得多，因为基类加载器已经可用并且已经被填充。
>
>如果您发现重启对于您的应用程序来说不够快，或者遇到类加载问题，则可以考虑从ZeroTurnaround中重新加载技术，例如JRebel。这些工作通过在加载类时重写类，使它们更易于重新加载。

#### 20.2.1. 记录条件评估中的更改

默认情况下，每次应用程序重新启动时，都会记录显示条件评估增量的报告。该报告显示了在您进行更改（如添加或删除Bean以及设置配置属性）时对应用程序自动配置的更改。

要禁用报告的日志记录，请设置以下属性:

```
spring.devtools.restart.log-condition-evaluation-delta=false
```

#### 20.2.2. 排除资源

某些资源不一定需要在更改时触发重新启动。例如，可以就地编辑Thymeleaf模板。默认情况下，更改 `/META-INF/maven`，`/META-INF/resources`，`/resources`，`/static`，`/public`或`/templates`中的资源不会触发重新启动，但会触发实时重新加载。如果你想自定义这些排除，你可以使用`spring.devtools.restart.exclude`属性。例如，要仅排除`/static`和`/public`，您将设置以下属性：

```
spring.devtools.restart.exclude=static/**,public/**
```

> 如果要保留这些默认值并添加其他排除项，请改为使用`spring.devtools.restart.additional-exclude`属性。

#### 20.2.3. 监控额外的路径

您可能希望在更改不在类路径中的文件时重新启动或重新加载应用程序。为此，请使用`spring.devtools.restart.additional-paths`属性来配置其他路径以监视更改。您可以使用前面介绍的`spring.devtools.restart.exclude`属性来控制其他路径下的更改是触发完全重新启动还是实时重新加载。

#### 20.2.4. 禁用重新启动

如果您不想使用重新启动功能，则可以使用`spring.devtools.restart.enabled`属性将其禁用。在大多数情况下，您可以在`application.properties`中设置此属性（这样做仍会初始化重新启动类加载器，但它不会监视文件更改）。

如果需要完全禁用重新启动支持（例如，因为它不适用于特定库），则在调用`SpringApplication.run（...）`之前，需要将`spring.devtools.restart.enabled` System属性设置为false，如如下例所示：

```java
public static void main(String[] args) {
	System.setProperty("spring.devtools.restart.enabled", "false");
	SpringApplication.run(MyApp.class, args);
}
```


#### 20.2.5. 使用触发文件

如果您使用持续编译更改文件的IDE，则可能只希望在特定时间触发重新启动。为此，您可以使用“触发文件”，这是一个特殊的文件，当您想要实际触发重新启动检查时必须对其进行修改。只有更改文件才会触发检查，并且仅在Devtools检测到必须执行某些操作时才会重新启动。触发文件可以手动更新或使用IDE插件更新。

要使用触发器文件，请将spring.devtools.restart.trigger-file属性设置为触发器文件的路径。

> 您可能希望将spring.devtools.restart.trigger-file设置为全局设置，以便所有项目的行为方式相同。



#### 20.2.6. 自定义重启类加载器

如前面的“Restart vs Reload”部分所述，重新启动功能通过使用两个类加载器来实现。对于大多数应用程序，这种方法运作良好但是，它有时会导致类加载问题。

默认情况下，IDE中的任何打开的项目都会加载“restart”类加载器，并且任何常规的`.jar`文件都会加载“base”类加载器。如果您使用多模块项目，并且不是每个模块都导入到IDE中，则可能需要自定义。为此，您可以创建一个 `META-INF/spring-devtools.properties` 文件。

`spring-devtools.properties`文件可以包含以`restart.exclude`和`restart.include`为前缀的属性。 include元素是应该被拉入到“重启”类加载器中的项目，而排除元素是应该下推到“基本”类加载器中的项目。该属性的值是应用于类路径的正则表达式模式，如以下示例所示：

```
restart.exclude.companycommonlibs=/mycorp-common-[\\w-]+\.jar
restart.include.projectcommon=/mycorp-myproj-[\\w-]+\.jar
```

> 所有属性键必须是唯一的。只要属性以`restart.include`或`restart.exclude`。已经被考虑了。
> 
> 加载类路径中的所有`META-INF/spring-devtools.properties`。您可以将文件打包到您的项目中，也可以打包到项目使用的库中

#### 20.2.7. 已知限制

对于使用标准`ObjectInputStream`进行反序列化的对象，重新启动功能无法正常工作。如果你需要反序列化数据，你可能需要结合使用Spring的`ConfigurableObjectInputStream`和`Thread.currentThread()`。`getContextClassLoader()`。 

不幸的是，有些第三方库反序列化而没有考虑上下文类加载器。如果您发现这样的问题，您需要向原作者请求修复。

### 20.3. 实时加载

`spring-boot-devtools`模块包含一个嵌入式LiveReload服务器，可用于在更改资源时触发浏览器刷新。 LiveReload浏览器扩展可免费用于livereload.com的Chrome，Firefox和Safari。 

如果您不想在应用程序运行时启动LiveReload服务器，则可以将`spring.devtools.livereload.enabled`属性设置为false。

> 一次只能运行一个LiveReload服务器。在开始应用程序之前，请确保没有其他LiveReload服务器正在运行。如果您从IDE启动多个应用程序，则只有第一个应用程序支持LiveReload。

### 20.4. 全局设置

您可以通过将名为`.spring-boot-devtools.properties`的文件添加到您的`$HOME`文件夹来配置全局devtools设置（请注意文件名以“。”开头）。添加到此文件的任何属性都适用于使用devtools的计算机上的所有Spring Boot应用程序。例如，要将重新启动配置为始终使用触发器文件，您可以添加以下属性：

~/.spring-boot-devtools.properties. 

```
spring.devtools.reload.trigger-file=.reloadtrigger
```

### 20.5. 远程应用

Spring Boot开发人员工具不限于本地开发。远程运行应用程序时，您还可以使用多个功能。远程支持是选择加入。要启用它，您需要确保devtools包含在重新打包的存档中，如下所示：

```
<build>
	<plugins>
		<plugin>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-maven-plugin</artifactId>
			<configuration>
				<excludeDevtools>false</excludeDevtools>
			</configuration>
		</plugin>
	</plugins>
</build>
```

然后你需要设置一个`spring.devtools.remote.secret`属性，如下例所示：

```
spring.devtools.remote.secret=mysecret
```

> 在远程应用程序上启用`spring-boot-devtools`存在安全风险。您不应该在生产部署上启用支持。

远程devtools支持分两部分提供：接受连接的服务器端端点以及您在IDE中运行的客户端应用程序。当设置了`spring.devtools.remote.secret`属性时，服务器组件会自动启用。客户端组件必须手动启动。

#### 20.5.1. 运行远程客户应用

远程客户端应用程序旨在从您的IDE中运行。您需要使用与您连接的远程项目相同的类路径运行`org.springframework.boot.devtools.RemoteSpringApplication`。应用程序的单个必需参数是它所连接的远程URL。

例如，如果您使用的是Eclipse或STS，并且您已经将一个名为my-app的项目部署到了​​Cloud Foundry，则可以执行以下操作：

* 从`Run`菜单中选择 `Run Configurations…​` 
* 创建一个新的 `Java Application`“启动配置”。 
* 浏览`my-app`项目。 
* 使用`org.springframework.boot.devtools.RemoteSpringApplication`作为主类。 
* 将`https://myapp.cfapps.io`添加到程序参数（或任何远程URL）。

正在运行的远程客户端可能类似于以下列表：

```
  .   ____          _                                              __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _          ___               _      \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` |        | _ \___ _ __  ___| |_ ___ \ \ \ \
 \\/  ___)| |_)| | | | | || (_| []::::::[]   / -_) '  \/ _ \  _/ -_) ) ) ) )
  '  |____| .__|_| |_|_| |_\__, |        |_|_\___|_|_|_\___/\__\___|/ / / /
 =========|_|==============|___/===================================/_/_/_/
 :: Spring Boot Remote :: 2.0.0.RELEASE

2015-06-10 18:25:06.632  INFO 14938 --- [           main] o.s.b.devtools.RemoteSpringApplication   : Starting RemoteSpringApplication on pwmbp with PID 14938 (/Users/pwebb/projects/spring-boot/code/spring-boot-devtools/target/classes started by pwebb in /Users/pwebb/projects/spring-boot/code/spring-boot-samples/spring-boot-sample-devtools)
2015-06-10 18:25:06.671  INFO 14938 --- [           main] s.c.a.AnnotationConfigApplicationContext : Refreshing org.springframework.context.annotation.AnnotationConfigApplicationContext@2a17b7b6: startup date [Wed Jun 10 18:25:06 PDT 2015]; root of context hierarchy
2015-06-10 18:25:07.043  WARN 14938 --- [           main] o.s.b.d.r.c.RemoteClientConfiguration    : The connection to http://localhost:8080 is insecure. You should use a URL starting with 'https://'.
2015-06-10 18:25:07.074  INFO 14938 --- [           main] o.s.b.d.a.OptionalLiveReloadServer       : LiveReload server is running on port 35729
2015-06-10 18:25:07.130  INFO 14938 --- [           main] o.s.b.devtools.RemoteSpringApplication   : Started RemoteSpringApplication in 0.74 seconds (JVM running for 1.105)
```

> 由于远程客户端使用与真实应用程序相同的类路径，它可以直接读取应用程序属性。这是如何读取`spring.devtools.remote.secret`属性并将其传递给服务器以进行身份​​验证。

> 始终建议使用`https://`作为连接协议，以便流量加密并且密码不会被拦截。

> 如果您需要使用代理来访问远程应用程序，请配置`spring.devtools.remote.proxy.host`和`spring.devtools.remote.proxy.port`属性。

#### 20.5.2. 远程更新

远程客户端以与本地重启相同的方式监视应用程序类路径的更改。任何更新的资源都会被推送到远程应用程序，并且（如果需要）会触发重新启动。如果您对使用本地没有的云服务的功能进行迭代，这会很有帮助。通常，远程更新和重新启动比完整的重建和部署周期快得多。

> 仅在远程客户端运行时才监视文件。如果在启动远程客户端之前更改文件，则不会将其推送到远程服务器。

## 21. 为生产环境打包应用

可执行的 jars 可用于生产部署。由于它们是独立的，它们也非常适合基于云的部署。 

对于额外的“生产就绪”功能，例如运行状况，审计和公制REST或JMX端点，请考虑添加`Spring Boot Actuator`。有关详细信息，请参见第V部分“Spring Boot Actuator：生产就绪功能”。

## 22. 接下来要阅读的内容

您现在应该了解如何使用Spring Boot以及您应遵循的一些最佳实践。您现在可以继续深入了解特定的Spring Boot功能，或者可以跳过并阅读Spring Boot的“生产准备”部分。


# IV. Spring Boot功能 

本节将介绍Spring Boot的细节。在这里，您可以了解您可能想要使用和定制的关键功能。如果您还没有这样做，您可能需要阅读“第II部分”，入门指南“”和“第III部分”，使用Spring Boot“”部分，以便您具备良好的基础知识。

## 23. SpringApplication 

SpringApplication类提供了一种方便的方法来引导从 main() 方法启动的Spring应用程序。在许多情况下，您可以委派到静态 `SpringApplication.run` 方法，如以下示例所示：

```java
public static void main(String[] args) {
	SpringApplication.run(MySpringConfiguration.class, args);
}
```

当你的应用启动时，你将看到以下输出：

```
  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::   v2.0.0.RELEASE

2013-07-31 00:08:16.117  INFO 56603 --- [           main] o.s.b.s.app.SampleApplication            : Starting SampleApplication v0.1.0 on mycomputer with PID 56603 (/apps/myapp.jar started by pwebb)
2013-07-31 00:08:16.166  INFO 56603 --- [           main] ationConfigServletWebServerApplicationContext : Refreshing org.springframework.boot.web.servlet.context.AnnotationConfigServletWebServerApplicationContext@6e5a8246: startup date [Wed Jul 31 00:08:16 PDT 2013]; root of context hierarchy
2014-03-04 13:09:54.912  INFO 41370 --- [           main] .t.TomcatServletWebServerFactory : Server initialized with port: 8080
2014-03-04 13:09:56.501  INFO 41370 --- [           main] o.s.b.s.app.SampleApplication 
```

默认情况下，会显示`INFO`日志消息，其中包括一些相关的启动详细信息，例如启动应用程序的用户。如果您需要`INFO`以外的日志级别，则可以按照第26.4节“日志级别”中所述对其进行设置，

### 23.1. 启动失败 

如果您的应用程序无法启动，注册的`FailureAnalyzers`将有机会提供专门的错误消息和具体操作来解决问题。例如，如果您在端口`8080`上启动Web应用程序，并且该端口已在使用中，则应该看到与以下消息类似的内容：

```
***************************
APPLICATION FAILED TO START
***************************

Description:

Embedded servlet container failed to start. Port 8080 was already in use.

Action:

Identify and stop the process that's listening on port 8080 or configure this application to listen on another port.
```
> Spring Boot提供了许多FailureAnalyzer实现，您可以添加自己的。

如果没有故障分析仪能够处理异常情况，您仍然可以显示完整的问题报告,以更好地了解问题所在。为此，您需要启用debug属性或为`org.springframework.boot.autoconfigure.logging.ConditionEvaluationReportLoggingListener`启用DEBUG日志记录。

例如，如果您使用`java -jar`运行应用程序，则可以按如下所示启用调试属性：

```
$ java -jar myproject-0.0.1-SNAPSHOT.jar --debug
```

### 23.2. 自定义Banner图

启动时打印的横幅可以通过将banner.txt文件添加到类路径中或通过将`spring.banner.location`属性设置为此类文件的位置来更改。如果文件的编码不是UTF-8，则可以设置`spring.banner.charset`。除了文本文件之外，还可以将`banner.gif`，`banner.jpg`或`banner.png`图像文件添加到类路径或设置`spring.banner.image.location`属性。图像被转换成ASCII艺术表现形式并打印在任何文字横幅上方。

在banner.txt文件中，您可以使用以下任何占位符：

Banner 变量
|变量|描述
|---|---
|${application.version}|在MANIFEST.MF中声明的应用程序的版本号。例如，Implementation-Version：1.0打印为1.0。
|${application.formatted-version}|应用程序的版本号，如MANIFEST.MF中所声明的并且格式化以显示（用括号括起来并以v作为前缀）。例如（v1.0）。
|${spring-boot.version}| Spring Boot 版本
|${spring-boot.formatted-version}| 您正在使用的Spring Boot版本，已格式化显示（用括号括起并以v作为前缀）。例如（v2.0.0.RELEASE）。
|${Ansi.NAME} (or ${AnsiColor.NAME}, ${AnsiBackground.NAME}, ${AnsiStyle.NAME})|其中NAME是ANSI转义代码的名称。有关详细信息，请参阅AnsiPropertySource。
|${application.title}|在MANIFEST.MF中声明的应用程序的标题。例如Implementation-Title：MyApp被打印为MyApp。

> 如果要以编程方式生成横幅，则可以使用`SpringApplication.setBanner（...）`方法。使用`org.springframework.boot.Banner`接口并实现您自己的`printBanner()`方法。

您还可以使用`spring.main.banner-mode`属性来确定横幅是否必须在System.out（控制台）上打印，发送到配置的记录器（日志），还是根本不生成（关闭）。

打印的横幅在以下名称下注册为singleton bean：s​​pringBootBanner。

YAML映射为false，因此如果要在应用程序中禁用横幅，请务必添加引号，如以下示例所示：

```
spring:
	main:
		banner-mode: "off"
```



### 23.3. 自定义SpringApplication 

如果`SpringApplication`的默认设置不符合您的喜好，您可以创建一个本地实例并对其进行自定义。例如，要关闭横幅，你可以写：

```java
public static void main(String[] args) {
	SpringApplication app = new SpringApplication(MySpringConfiguration.class);
	app.setBannerMode(Banner.Mode.OFF);
	app.run(args);
}
```

> 传递给SpringApplication的构造函数参数是Spring bean的配置源。在大多数情况下，这些都是对@Configuration类的引用，但它们也可能是对XML配置或应扫描的包的引用。

也可以通过使用`application.properties`文件来配置`SpringApplication`。有关详细信息，请参阅第24章，外部化配置。

有关配置选项的完整列表，请参阅 SpringApplication Javadoc。


### 23.4. Fluent Builder API 

如果您需要构建`ApplicationContext`层次结构（具有父/子关系的多个上下文），或者如果您更愿意使用“流利”构建器API，则可以使用`SpringApplicationBuilder`。

通过`SpringApplicationBuilder`，您可以将多个方法调用链接在一起，并包含可以创建层次结构的父方法和子方法，如以下示例所示：

```java
new SpringApplicationBuilder()
		.sources(Parent.class)
		.child(Application.class)
		.bannerMode(Banner.Mode.OFF)
		.run(args);
	
```

> 创建ApplicationContext层次结构时有一些限制。例如，Web组件必须包含在子上下文中，并且父环境和子环境都使用相同的环境。有关完整的细节，请参阅SpringApplicationBuilder Javadoc。

### 23.5. 应用程序事件和监听器 

除了通常的Spring框架事件（如ContextRefreshedEvent）之外，SpringApplication还会发送一些其他应用程序事件。

随着您的应用程序运行，应用程序事件按以下顺序发送：

1. ApplicationStartingEvent在运行开始时但在任何处理之前发送，除了注册侦听器和初始化器之外。 
2. 当在上下文中使用的环境是已知的但在创建上下文之前发送ApplicationEnvironmentPreparedEvent。 
3. ApplicationPreparedEvent在刷新开始之前但在bean定义加载之后发送。 
4. 在刷新上下文之后但在调用任何应用程序和命令行参赛者之前发送ApplicationStartedEvent。 
5. ApplicationReadyEvent在任何应用程序和命令行参数被调用后发送。它表示应用程序已准备好为请求提供服务。 
6. 如果启动时出现异常，则发送ApplicationFailedEvent。

> 您通常不需要使用应用程序事件，但可以方便地知道它们存在。在内部，Spring Boot使用事件来处理各种任务。

应用程序事件通过使用Spring Framework的事件发布机制发送。该机制的一部分确保发布给子上下文中侦听器的事件也发布给任何祖先上下文中的侦听器。因此，如果您的应用程序使用SpringApplication实例的层次结构，则侦听器可能会收到同一类型应用程序事件的多个实例。

为了让你的监听器区分上下文事件和后代上下文事件，它应该请求它的应用上下文被注入，然后比较注入的上下文和事件的上下文。上下文可以通过实现`ApplicationContextAware`注入，或者如果侦听器是bean，则可以通过使用`@Autowired`注入。


### 23.6. Web环境

`SpringApplication`试图代表您创建正确类型的`ApplicationContext`。默认情况下，使用`AnnotationConfigApplicationContext`或`AnnotationConfigServletWebServerApplicationContext`，具体取决于您是否在开发Web应用程序。

用于确定“网络环境”的算法相当简单（它基于几个类的存在）。如果你需要重写默认值，你可以使用`setWebEnvironment(boolean webEnvironment)`。

也可以通过调用`setApplicationContextClass(...) `来完全控制`ApplicationContext`类型。

在JUnit测试中使用`SpringApplication`时，通常需要调用`setWebEnvironment(false)`。

### 23.7. 访问应用程序参数 

如果您需要访问传递给SpringApplication.run（...）的应用程序参数，则可以注入一个org.springframework.boot.ApplicationArguments bean。 ApplicationArguments接口提供对原始String []参数以及分析的选项和非选项参数的访问，如以下示例中所示：

```java
import org.springframework.boot.*
import org.springframework.beans.factory.annotation.*
import org.springframework.stereotype.*

@Component
public class MyBean {

	@Autowired
	public MyBean(ApplicationArguments args) {
		boolean debug = args.containsOption("debug");
		List<String> files = args.getNonOptionArgs();
		// if run with "--debug logfile.txt" debug=true, files=["logfile.txt"]
	}
}
```

> Spring Boot还向Spring环境注册了一个`CommandLinePropertySource`。这使您可以通过使用`@Value`注释来注入单个应用程序参数。

### 23.8. 使用ApplicationRunner或CommandLineRunner 

如果你需要在SpringApplication启动后运行一些特定的代码，你可以实现`ApplicationRunner`或者`CommandLineRunner`接口。两个接口都以相同的方式工作，并提供一个单独的运行方法，这个方法在`SpringApplication.run(...)`完成之前被调用。

CommandLineRunner接口作为一个简单的字符串数组提供对应用程序参数的访问，而ApplicationRunner使用前面讨论的ApplicationArguments接口。以下示例显示带有run方法的CommandLineRunner：

```java
import org.springframework.boot.*
import org.springframework.stereotype.*

@Component
public class MyBean implements CommandLineRunner {

	public void run(String... args) {
		// Do something...
	}
}
```

如果定义了几个必须以特定顺序调用的`CommandLineRunner`或`ApplicationRunner bean`，则可以另外实现`org.springframework.core.Ordered`接口或使用`org.springframework.core.annotation.Order`注释。

### 23.9. 申请退出 

每个`SpringApplication`都向JVM注册一个关闭钩子，以确保`ApplicationContext`在退出时正常关闭。可以使用所有标准的Spring生命周期回调（如DisposableBean接口或@PreDestroy注释）。

另外，如果在调用 `SpringApplication.exit()` 时希望返回特定的退出代码，那么bean可以实现`org.springframework.boot.ExitCodeGenerator`接口。然后可以将此退出代码传递给`System.exit()` 以将其作为状态代码返回，如以下示例中所示：

```java
@SpringBootApplication
public class ExitCodeApplication {

	@Bean
	public ExitCodeGenerator exitCodeGenerator() {
		return () -> 42;
	}

	public static void main(String[] args) {
		System.exit(SpringApplication
				.exit(SpringApplication.run(ExitCodeApplication.class, args)));
	}

}
```
另外，`ExitCodeGenerator`接口可能由例外实现。遇到这样的异常时，Spring Boot将返回由实现的`getExitCode()` 方法提供的退出代码。

### 23.10. 管理功能

通过指定`spring.application.admin.enabled`属性，可以为应用程序启用与管理相关的功能。这暴露了平台`MBeanServer`上的`SpringApplicationAdminMXBean`。您可以使用此功能远程管理您的`Spring Boot`应用程序。此功能对于任何服务包装器实现也可能有用。

> 如果您想知道应用程序在哪个HTTP端口上运行，请使用`local.server.port`的密钥获取该属性。

> 启用此功能时要小心，因为MBean公开了关闭应用程序的方法。



## 24. 外部化配置

Spring Boot允许您将配置外部化，以便您可以在不同环境中使用相同的应用程序代码。您可以使用属性文件，YAML文件，环境变量和命令行参数来外部化配置。属性值可以通过使用`@Value`注解直接注入到bean中，通过Spring的`Environment`抽象来访问，或者通过`@ConfigurationProperties`绑定到结构化对象。

Spring Boot使用非常特殊的PropertySource命令，该命令旨在允许明智地重写值。属性按以下顺序考虑：

1. 在主目录上开发Devtools全局设置属性（当devtools处于活动状态时，〜/ .spring-boot-devtools.properties）。
2. 在你的测试中使用@TestPropertySource注解。
3. 测试中的@SpringBootTest＃属性注释属性。
4. 命令行参数。
5. 来自SPRING_APPLICATION_JSON的属性（嵌入在环境变量或系统属性中的内联JSON）。
6. ServletConfig初始化参数。
7. ServletContext初始化参数。
8. 来自java：comp / env的JNDI属性。
9. Java系统属性（System.getProperties()）
10. OS环境变量。
11. 仅具有随机属性的RandomValuePropertySource。
12. 打包jar（application-{profile} .properties和YAML）之外的特定于配置文件的应用程序属性。
13. 打包在您的jar（application-{profile} .properties和YAML）中的特定于配置文件的应用程序属性。
14. 应用程序属性在打包的jar之外（application.properties和YAML）
15. 打包在jar中的应用程序属性（application.properties和YAML）
16. @Configuration类的@PropertySource注释。
17. 默认属性（通过设置SpringApplication.setDefaultProperties指定）

为了提供一个具体的例子，假设你开发了一个使用name属性的@Component，如下例所示：

```java
import org.springframework.stereotype.*
import org.springframework.beans.factory.annotation.*

@Component
public class MyBean {

    @Value("${name}")
    private String name;

    // ...
}
```

在您的应用程序类路径中（例如，在您的jar中），您可以拥有一个`application.properties`文件，该文件为名称提供了一个合理的默认属性值。在新环境中运行时，可以在jar外部提供一个`application.properties`文件来覆盖该名称。对于一次性测试，您可以使用特定的命令行开关启动（例如，`java -jar app.jar --name ="Spring"`）。


### 24.1. 配置随机值

RandomValuePropertySource用于注入随机值（例如，注入秘密或测试用例）。它可以产生整数，长整数，uuids或字符串，如下例所示：

```
my.secret=${random.value}
my.number=${random.int}
my.bignumber=${random.long}
my.uuid=${random.uuid}
my.number.less.than.ten=${random.int(10)}
my.number.in.range=${random.int[1024,65536]}
```

`random.int *`语法是`OPEN value（，max）CLOSE`，其中OPEN，CLOSE是任何字符和值，max是整数。如果提供最大值，则值是最小值，最大值是最大值（不包括）。

### 24.2. 访问命令行属性

默认情况下，`SpringApplication`将任何命令行选项参数（即以 - 开头的参数，例如`--server.port = 9000）`转换为属性并将它们添加到Spring环境中。如前所述，命令行属性始终优先于其他属性源。 

如果您不想将命令行属性添加到环境中，可以使用`SpringApplication.setAddCommandLineProperties（false）`将其禁用。

### 24.3. 应用程序属性文件

`SpringApplication`从以下位置的`application.properties`文件加载属性并将它们添加到Spring环境中：

1. 当前目录的 /config 子目录
2. 当前目录
3. 类路径 /config 包
4. 类路径根目录

该列表按优先顺序排列（在列表中较高的位置定义的属性会覆盖在较低位置定义的属性）。

> 您也可以使用YAML（'.yml'）文件替代'.properties'。

如果您不喜欢application.properties作为配置文件名，则可以通过指定一个spring.config.name环境属性来切换到另一个文件名。您还可以使用spring.config.location环境属性（这是逗号分隔的目录位置或文件路径列表）引用显式位置。以下示例显示如何指定不同的文件名称：

```
$ java -jar myproject.jar --spring.config.name=myproject
```

以下示例显示如何指定两个位置：

```
$ java -jar myproject.jar --spring.config.location=classpath:/default.properties,classpath:/override.properties
```

spring.config.name和spring.config.location很早就用来确定哪些文件必须被加载，因此它们必须被定义为环境属性（通常是OS环境变量，系统属性或命令行参数）。

如果`spring.config.location`包含目录（与文件相对），它们应该以`/`结尾（并且在运行时加载在加载之前从`spring.config.name`生成的名称，包括配置文件特定的文件名）。在`spring.config.location`中指定的文件按原样使用，不支持特定于配置文件的变体，并且被特定于配置文件的特性覆盖。

配置位置按相反顺序搜索。默认情况下，配置的位置是`classpath:/，classpath:/ config/，file:./，file:./ config/`。结果搜索顺序如下：

1. file:./config/
2. file:./
3. classpath:/config/
4. classpath:/

当通过使用`spring.config.location`配置自定义配置位置时，它们会替换默认位置。例如，如果使用值 `classpath:/custom-config/，file:./custom-config/` 配置了spring.config.location，则搜索顺序如下所示：

1. file:./custom-config/
2. classpath:custom-config/

或者，使用`spring.config.additional-location`配置自定义配置位置时，除了默认位置以外，还会使用它们。在默认位置之前搜索其他位置。例如，如果配置了的其他位置：`classpath/custom-config/，file:./ custom-config/`，则搜索顺序变为以下内容：

1. file:./custom-config/
2. classpath:custom-config/
3. file:./config/
4. file:./
5. classpath:/config/
6. classpath:/

此搜索顺序可让您在一个配置文件中指定默认值，然后在另一配置文件中选择性地覆盖这些值。您可以在其中一个默认位置为`application.properties`（或您使用`spring.config.name`选择的其他基本名称）提供应用程序的默认值。这些默认值可以在运行时被置于其中一个自定义位置的不同文件覆盖。

> 如果使用环境变量而非系统属性，则大多数操作系统不允许使用句点分隔的键名称，但可以改为使用下划线（例如，`SPRING_CONFIG_NAME`而不是`spring.config.name`）。
> 
> 如果您的应用程序在容器中运行，那么可以使用JNDI属性（在java:comp/env中）或servlet上下文初始化参数，而不是使用环境变量或系统属性。

### 24.4. 配置文件特定的属性

除了application.properties文件外，还可以使用以下命名约定来定义配置文件特定属性：application- {profile} .properties。如果未设置活动配置文件，则环境具有一组默认配置文件（默认情况下为[默认值]）。换句话说，如果没有显式激活配置文件，则会加载来自application-default.properties的属性。

特定于配置文件的属性从标准application.properties的相同位置加载，特定于配置文件的文件始终覆盖非特定的文件，无论配置文件特定的文件是否位于打包的jar内部或外部。

如果指定了多个配置文件，则应用最后赢取策略。例如，由spring.profiles.active属性指定的配置文件将添加到通过SpringApplication API配置的配置文件之后，因此优先。

> 如果您在spring.config.location中指定了任何文件，则不会考虑这些文件的特定于配置文件的变体。如果您还想使用配置文件特定的属性，请使用spring.config.location中的目录。

### 24.5. 属性中的占位符

使用它们时，`application.properties`中的值将通过现有环境进行过滤，因此您可以引用回以前定义的值（例如，从System properties）。

```
app.name=MyApp
app.description=${app.name} is a Spring Boot application
```

> 您也可以使用这种技术来创建现有Spring Boot属性的“简短”变体。有关详细信息，请参见第74.4节“使用简短'命令行参数”。

### 24.6. 使用 YAML 文件代替 Properties 文件

YAML是JSON的超集，因此是用于指定分层配置数据的便利格式。 SpringApplication类自动支持YAML作为属性的替代方法，只要您在类路径中具有SnakeYAML库。

> 如果你使用“Starters”，SnakeYAML由`spring-boot-starter`自动提供。

#### 24.6.1. 加载 YAML

Spring框架提供了两个方便的类，可以用来加载YAML文档。 `YamlPropertiesFactoryBean`将YAML加载为属性，`YamlMapFactoryBean`将YAML加载为Map。

例如，请考虑以下YAML文档：

```
environments:
	dev:
		url: http://dev.example.com
		name: Developer Setup
	prod:
		url: http://another.example.com
		name: My Cool App
```

前面的示例将转换为以下属性：

```
environments.dev.url=http://dev.example.com
environments.dev.name=Developer Setup
environments.prod.url=http://another.example.com
environments.prod.name=My Cool App
```

YAML列表被表示为带有[index] dereferencers的属性键。例如，请考虑以下YAML：

```
my:
servers:
	- dev.example.com
	- another.example.com
```
前面的例子将被转换成这些属性：

```
my.servers[0]=dev.example.com
my.servers[1]=another.example.com
```

要通过使用Spring DataBinder实用程序（这是@ConfigurationProperties的作用）绑定到类似的属性，您需要在java.util.List（或Set）类型的目标bean中拥有一个属性，并且您需要提供一个setter或用一个可变值初始化它。例如，以下示例绑定到以前显示的属性：

```java
@ConfigurationProperties(prefix="my")
public class Config {

	private List<String> servers = new ArrayList<String>();

	public List<String> getServers() {
		return this.servers;
	}
}
```

> 当列表配置在多个地方时，通过替换整个列表来覆盖作品。在前面的示例中，当my.servers在多个位置定义时，PropertySource中具有更高优先级的整个列表将覆盖该列表的任何其他配置。逗号分隔列表和YAML列表都可用于完全覆盖列表的内容。




#### 24.6.2. 在Spring环境中展示YAML文件

`YamlPropertySourceLoader`类可用于在Spring环境中将YAML作为`PropertySource`公开。这样做可让您使用带有占位符语法的`@Value`注释来访问YAML属性。

#### 24.6.3. 多环境 YAML 文件

您可以通过使用`spring.profiles`键指定文档适用的时间，在单个文件中指定多个特定于配置文件的YAML文档，如以下示例所示：

```
server:
	address: 192.168.1.100
---
spring:
	profiles: development
server:
	address: 127.0.0.1
---
spring:
	profiles: production
server:
	address: 192.168.1.120
```

在前面的示例中，如果开发配置文件处于活动状态，则`server.address`属性为`127.0.0.1`。同样，如果生产配置文件处于活动状态，则`server.address`属性为`192.168.1.120`。如果开发和生产配置文件未启用，则该属性的值为`192.168.1.100`。

如果应用程序上下文启动时没有显式激活，则激活默认配置文件。因此，在下面的YAML中，我们为`spring.security.user.password`设置了一个值，该值仅在“默认”配置文件中可用：

```
server:
  port: 8000
---
spring:
  profiles: default
  security:
    user:
      password: weak
```

而在以下示例中，由于密码未附加到任何配置文件，因此始终设置密码，必须根据需要在所有其他配置文件中明确重置该密码：

```
server:
  port: 8000
spring:
  security:
    user:
      password: weak
```

通过使用spring.profiles元素指定的Spring配置文件可以通过使用！字符。如果为单个文档指定了否定配置文件和非否定配置文件，则至少有一个非否定配置文件必须匹配，且不存在否定配置文件可能匹配。

#### 24.6.4. YAML 缺点

YAML文件不能使用@PropertySource批注加载。因此，如果您需要以这种方式加载值，则需要使用属性文件。

#### 24.6.5. 合并 YAML 列表

正如我们前面所展示的，任何YAML内容最终都会转换为属性。当通过配置文件覆盖“列表”属性时，该过程可能不直观。

例如，假定默认情况下名称和描述属性为空的MyPojo对象。以下示例公开了AcmeProperties中的MyPojo对象列表：

```java
@ConfigurationProperties("acme")
public class AcmeProperties {

	private final List<MyPojo> list = new ArrayList<>();

	public List<MyPojo> getList() {
		return this.list;
	}

}
```

考虑以下配置：

```
acme:
  list:
    - name: my name
      description: my description
---
spring:
  profiles: dev
acme:
  list:
       - name: my another name
```

当在多个配置文件中指定一个集合时，将使用具有最高优先级（仅限那个）的集合。考虑下面的例子：

```
acme:
  list:
	- name: my name
	  description: my description
	- name: another name
	  description: another description
---
spring:
  profiles: dev
acme:
  list:
	 - name: my another name
```

在前面的示例中，如果开发人员配置文件处于活动状态，则AcmeProperties.list包含一个MyPojo条目（名称为我的另一个名称和空描述）。



### 24.7. 类型安全的配置属性

使用`@Value(“$ {property}”)`注释来注入配置属性有时会很麻烦，特别是如果您使用多个属性或者您的数据本质上是分层的。 Spring Boot提供了另一种使用属性的方法，可以让强类型bean管理和验证应用程序的配置，如以下示例所示：

```java
package com.example;

import java.net.InetAddress;
import java.util.ArrayList;
import java.util.Collections;
import java.util.List;

import org.springframework.boot.context.properties.ConfigurationProperties;

@ConfigurationProperties("acme")
public class AcmeProperties {

	private boolean enabled;

	private InetAddress remoteAddress;

	private final Security security = new Security();

	public boolean isEnabled() { ... }

	public void setEnabled(boolean enabled) { ... }

	public InetAddress getRemoteAddress() { ... }

	public void setRemoteAddress(InetAddress remoteAddress) { ... }

	public Security getSecurity() { ... }

	public static class Security {

		private String username;

		private String password;

		private List<String> roles = new ArrayList<>(Collections.singleton("USER"));

		public String getUsername() { ... }

		public void setUsername(String username) { ... }

		public String getPassword() { ... }

		public void setPassword(String password) { ... }

		public List<String> getRoles() { ... }

		public void setRoles(List<String> roles) { ... }

	}
}
```

前面的POJO定义了以下属性：

1. acme.enabled，默认值为false。
2. acme.remote-address，可以从String强制类型。
3. acme.security.username，带有一个嵌套的“安全”对象，其名称由属性的名称确定。特别是，返回类型根本就没有使用，可能是SecurityProperties。
4. acme.security.password
5. acme.security.roles 使用String类型的集合。

> getters和setter通常是强制性的，因为绑定是通过标准的Java Beans属性描述符进行的，就像在Spring MVC中一样。在以下情况下可能会忽略setter：
> 只要它们被初始化，Maps就需要一个getter，但不一定是setter，因为它们可以通过绑定器进行变异。
> 集合和数组可以通过索引（通常使用YAML）或使用单个逗号分隔值（属性）来访问。在后一种情况下，制定者是强制性的。我们建议始终为这些类型添加setter。如果初始化一个集合，确保它不是不可变的（如上例）。
> 如果嵌套的POJO属性被初始化（如前面例子中的Security域），则不需要setter。如果您希望活页夹通过使用其默认构造函数即时创建实例，则需要一个setter。
> 
> 有些人使用Project Lombok来自动添加getter和setter。确保Lombok不会为这种类型生成任何特定的构造函数，因为它被容器自动使用来实例化对象。 
> 
> 另请参阅@Value和@ConfigurationProperties之间的区别。

```
@Configuration
@EnableConfigurationProperties(AcmeProperties.class)
public class MyConfiguration {

}
```

> 当以这种方式注册`@ConfigurationProperties` bean时，该bean具有常规名称：`<prefix> - <fqn>`，其中`<prefix>`是`@ConfigurationProperties`注释中指定的环境键前缀，<fqn>是完全限定的名称豆。如果注释没有提供任何前缀，则只使用bean的完全限定名称。 上例中的bean名称是`acme-com.example.AcmeProperties`。

即使前面的配置为AcmeProperties创建了一个常规bean，我们也建议`@ConfigurationProperties`只处理环境，特别是不会从上下文中注入其他bean。话虽如此，`@EnableConfigurationProperties`注释也会自动应用到您的项目中，以便通过环境配置任何使用`@ConfigurationProperties`注释的现有bean。您可以通过确保`AcmeProperties`已经是一个bean来快捷`MyConfiguration`，如以下示例所示：

```
@Component
@ConfigurationProperties(prefix="acme")
public class AcmeProperties {

	// ... see the preceding example

}
```

这种配置风格对SpringApplication外部YAML配置特别有效，如以下示例所示：

```
# application.yml

acme:
	remote-address: 192.168.1.1
	security:
		username: admin
		roles:
		  - USER
		  - ADMIN

# additional configuration as required
```

要使用@ConfigurationProperties bean，可以像使用其他bean一样注入它们，如以下示例所示：

```
@Service
public class MyService {

	private final AcmeProperties properties;

	@Autowired
	public MyService(AcmeProperties properties) {
	    this.properties = properties;
	}

 	//...

	@PostConstruct
	public void openConnection() {
		Server server = new Server(this.properties.getRemoteAddress());
		// ...
	}

}
```

> 使用@ConfigurationProperties还可以生成元数据文件，IDE可以使用这些文件为自己的密钥提供自动完成功能。有关详细信息，请参阅附录B，配置元数据附录。


#### 24.7.1. 第三方配置

除了使用`@ConfigurationProperties`注解一个类，您还可以在public @Bean方法上使用它。如果要将属性绑定到不在您控制之外的第三方组件，则这样做会特别有用。

要从Environment属性配置一个bean，将`@ConfigurationProperties`添加到它的bean注册中，如以下示例所示：

```
@ConfigurationProperties(prefix = "another")
@Bean
public AnotherComponent anotherComponent() {
	...
}
```

#### 24.7.2. 轻松的绑定

Spring Boot使用一些宽松的规则将环境属性绑定到@ConfigurationProperties bean，因此不需要在Environment属性名称和bean属性名称之间完全匹配。常见的例子中，这是有用的，包括破折号分隔的环境属性（例如，上下文路径绑定到contextPath）和大写的环境属性（例如，PORT绑定到端口）。

例如，请考虑以下`@ConfigurationProperties`类：

```java
@ConfigurationProperties(prefix="acme.my-project.person")
public class OwnerProperties {

	private String firstName;

	public String getFirstName() {
		return this.firstName;
	}

	public void setFirstName(String firstName) {
		this.firstName = firstName;
	}

}
```

在前面的示例中，可以使用以下属性名称：

|属性|说明
|---|---
|acme.my-project.person.firstName|标准骆驼大小写语法
|acme.my-project.person.first-name|Kebab情况，建议在.properties和.yml文件中使用。
|acme.my-project.person.first_name|下划线表示法，这是在.properties和.yml文件中使用的替代格式
|ACME_MYPROJECT_PERSON_FIRSTNAME|大写格式，使用系统环境变量时建议使用。

> 注释的前缀值必须是kebab格式（小写，并用 `-` 分隔，例如`acme.my-project.person`）。



#### 24.7.3. 属性转换和转换时间 

当Spring Boot绑定到`@ConfigurationProperties` bean时，它会尝试将外部应用程序属性强制转换为正确的类型。如果您需要自定义类型转换，则可以提供`ConversionService` bean（带有一个名为`conversionService`的bean）或定制属性编辑器（通过CustomEditorConfigurer bean）或定制转换器（带有注释为`@ConfigurationPropertiesBinding`的bean定义）。

> 由于此bean在应用程序生命周期中很早被请求，因此请确保限制ConversionService所使用的依赖项。通常，您需要的任何依赖项可能在创建时未完全初始化。如果不需要配置密钥强制转换，并且只依赖使用`@ConfigurationPropertiesBinding`限定的自定义转换器，则可能需要重命名自定义ConversionService。

转换持续时间 

Spring Boot有专门的支持来表达持续时间。如果公开`java.time.Duration`属性，则应用程序属性中的以下格式可用：

* 常规的长表示法（除非指定@DefaultUnit，否则使用毫秒作为默认单位）
* java.util.Duration使用的标准ISO-8601格式
* 值和单位耦合的更可读的格式（例如，10s表示10秒）

考虑下面的例子：

```java
@ConfigurationProperties("app.system")
public class AppSystemProperties {

	@DurationUnit(ChronoUnit.SECONDS)
	private Duration sessionTimeout = Duration.ofSeconds(30);

	private Duration readTimeout = Duration.ofMillis(1000);

	public Duration getSessionTimeout() {
		return this.sessionTimeout;
	}

	public void setSessionTimeout(Duration sessionTimeout) {
		this.sessionTimeout = sessionTimeout;
	}

	public Duration getReadTimeout() {
		return this.readTimeout;
	}

	public void setReadTimeout(Duration readTimeout) {
		this.readTimeout = readTimeout;
	}

}
```

要指定30秒的会话超时，30，PT30S和30s都是等效的。 500ms的读取超时时间可以采用以下任意形式指定：500，PT0.5S和500ms。

> 如果您正在使用仅使用Long来表示持续时间的先前版本进行升级，请确保在切换到持续时间的情况下定义单位（使用@DefaultUnit），如果它不是毫秒。这样做可以提供透明的升级途径，同时支持更丰富的格式。



#### 24.7.4. @ConfigurationProperties Validation

Spring Boot会在Spring的`@Validated`注释中注释时尝试验证`@ConfigurationProperties`类。您可以直接在配置类上使用JSR-303 javax.validation约束注释。为此，请确保您的类路径上包含一个兼容的JSR-303实现，然后将约束注释添加到您的字段中，如以下示例所示：

```
@ConfigurationProperties(prefix="acme")
@Validated
public class AcmeProperties {

	@NotNull
	private InetAddress remoteAddress;

	// ... getters and setters

}
```

> 您还可以通过注释`@Bean`方法触发验证，该方法使用`@Validated`创建配置属性。

尽管嵌套属性在绑定时也会被验证，但最好还是将相关字段注释为`@Valid`。这确保即使未找到嵌套属性也会触发验证。以下示例基于前面的`AcmeProperties`示例构建：

```java
@ConfigurationProperties(prefix="acme")
@Validated
public class AcmeProperties {

	@NotNull
	private InetAddress remoteAddress;

	@Valid
	private final Security security = new Security();

	// ... getters and setters

	public static class Security {

		@NotEmpty
		public String username;

		// ... getters and setters

	}

}
```

你也可以通过创建一个名为`configurationPropertiesValidator`的bean定义来添加一个自定义的`Spring Validator`。 `@Bean`方法应该声明为静态的。配置属性validator是在应用程序生命周期的早期创建的，并且将`@Bean`方法声明为静态，这样就可以创建bean而无需实例化`@Configuration`类。这样做可以避免早期实例化可能导致的任何问题。有一个属性验证示例显示了如何设置。

> `spring-boot-actuator`模块包含一个公开所有`@ConfigurationProperties` bean的端点。将您的Web浏览器指向 `/actuator/configprops` 或使用等效的JMX端点。详细信息请参见“生产准备就绪功能”部分。


#### 24.7.5. @ConfigurationProperties vs. @Value

`@Value`注释是一个核心容器功能，它不提供与类型安全配置属性相同的功能。下表总结了`@ConfigurationProperties`和`@Value`支持的功能：

|特征|@ConfigurationProperties| @Value
|---|---|---
|Relaxed binding|Yes|No
|Meta-data support|Yes|No
|SpEL evaluation|No|Yes

如果您为自己的组件定义了一组配置密钥，我们建议您将它们分组到POJO中，并使用`@ConfigurationProperties`进行注释。您还应该意识到，由于`@Value`不支持放宽绑定，因此如果您需要通过使用环境变量来提供值，则它不是一个好选择。 

最后，虽然可以在`@Value`中编写`SpEL`表达式，但这些表达式不会从应用程序属性文件中处理。

## 25. Profiles 

Spring Profiles提供了一种分离部分应用程序配置的方法，并使其仅在特定环境中可用。可以使用@Profile标记任何@Component或@Configuration，以限制何时加载它，如以下示例所示：

```java
@Configuration
@Profile("production")
public class ProductionConfiguration {

	// ...

}
```

您可以使用`spring.profiles.active`环境属性来指定哪些配置文件处于活动状态。您可以用本章前面所述的任何方式指定属性。例如，您可以将其包含在`application.properties`中，如以下示例所示：

```
spring.profiles.active=dev,hsqldb
```

您也可以使用以下开关在命令行上指定它：`--spring.profiles.active = dev，hsqldb`

### 25.1. 添加活动配置文件 

`spring.profiles.active`属性遵循与其他属性相同的排序规则：最高的PropertySource获胜。这意味着您可以在`application.properties`中指定活动配置文件，然后使用命令行开关替换它们。

有时候，将配置文件特定的属性添加到活动配置文件而不是替换它们会很有用。 `spring.profiles.include`属性可用于无条件添加活动配置文件。 SpringApplication入口点还具有用于设置其他配置文件的Java API（即，在由`spring.profiles.active`属性激活的那些配置文件之上）。请参阅SpringApplication中的`setAdditionalProfiles()`方法。

例如，当使用交换机运行具有以下属性的应用程序`--spring.profiles.active = prod`时，proddb和prodmq配置文件也会被激活：

```
---
my.property: fromyamlfile
---
spring.profiles: prod
spring.profiles.include:
  - proddb
  - prodmq
```

> 请记住，`spring.profiles`属性可以在YAML文档中定义，以确定何时将此特定文档包含在配置中。有关更多详细信息，请参见第74.7节“根据环境更改配置”。

### 25.2. 编程设置配置文件 

您可以通过在应用程序运行之前调用`SpringApplication.setAdditionalProfiles(...)`以编程方式设置活动配置文件。通过使用Spring的`ConfigurableEnvironment`接口也可以激活配置文件。

### 25.3. 配置文件特定的配置文件 

将`application.properties`（或`application.yml`）和通过`@ConfigurationProperties`引用的文件的特定于配置文件的变体视为文件并加载。有关详细信息，请参见“第24.4节”特定于配置文件的属性“。

## 26.日志 

Spring Boot使用`Commons Logging`进行所有内部日志记录，但将底层日志实现保持打开状态。为Java Util Logging，Log4J2和Logback提供了默认配置。在每种情况下，记录器都预先配置为使用控制台输出，并提供可选的文件输出。

默认情况下，如果您使用“Starters”，则使用Logback进行日志记录。还包括适当的Logback路由，以确保使用Java Util日志记录，Commons日志记录，Log4J或SLF4J的依赖库全部正常工作。

> Java有很多可用的日志框架。如果上面的列表看起来很混乱，请不要担心。一般来说，你不需要改变你的日志依赖性，Spring Boot的默认工作就可以。


### 26.1. 日志格式 

Spring Boot的默认日志输出类似于以下示例：

```
2014-03-05 10:57:51.112  INFO 45469 --- [           main] org.apache.catalina.core.StandardEngine  : Starting Servlet Engine: Apache Tomcat/7.0.52
2014-03-05 10:57:51.253  INFO 45469 --- [ost-startStop-1] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2014-03-05 10:57:51.253  INFO 45469 --- [ost-startStop-1] o.s.web.context.ContextLoader            : Root WebApplicationContext: initialization completed in 1358 ms
2014-03-05 10:57:51.698  INFO 45469 --- [ost-startStop-1] o.s.b.c.e.ServletRegistrationBean        : Mapping servlet: 'dispatcherServlet' to [/]
2014-03-05 10:57:51.702  INFO 45469 --- [ost-startStop-1] o.s.b.c.embedded.FilterRegistrationBean  : Mapping filter: 'hiddenHttpMethodFilter' to: [/*]
```

以下项目被输出：

* 日期和时间：毫秒精度，可轻松排序。
* 日志级别：ERROR, WARN, INFO, DEBUG, or TRACE.
* 进程ID
* `---`分隔符来区分实际日志消息的开始。
* 线程名称：括在方括号中（可能会截断控制台输出）。
* 记录器名称：这通常是源类名称（通常缩写）。
* 日志消息

> Logback没有FATAL级别。它被映射到ERROR。


### 26.2. 控制台输出 

默认日志配置会在写入消息时将消息回传给控制台。默认情况下，将记录ERROR级别，WARN级别和INFO级别的消息。您还可以通过使用`--debug`标志启动应用程序来启用“调试”模式。

```
$ java -jar myapp.jar --debug
```

> 你也可以在`application.properties`中指定debug = true。

当启用调试模式时，将选择核心记录器（嵌入式容器，Hibernate和Spring Boot）配置为输出更多信息。启用调试模式不会将应用程序配置为使用DEBUG级别记录所有消息。

或者，您可以通过使用`--trace`标志（或`application.properties`中的`trace= true`）启动应用程序来启用“跟踪”模式。这样做可以为选择的核心记录器（嵌入式容器，Hibernate模式生成和整个Spring产品组合）启用跟踪记录。



#### 26.2.1. 彩色编码输出 

如果您的终端支持ANSI，则会使用彩色输出来提高可读性。您可以将`spring.output.ansi.enabled`设置为受支持的值来覆盖自动检测。

颜色编码通过使用`％clr`转换字进行配置。最简单的形式是，转换器根据日志级别为输出着色，如以下示例所示：

```
%clr(%5p)
```

下表描述了日志级别到颜色的映射：

|级别|颜色
|---|---
|FATAL|Red
|ERROR|Red
|WARN|Yellow
|INFO|Green
|DEBUG|Green
|TRACE|Green

或者，您可以通过将其作为选项提供给转换来指定应使用的颜色或样式。例如，要使文本变为黄色，请使用以下设置：

```
%clr(%d{yyyy-MM-dd HH:mm:ss.SSS}){yellow}
```
支持以下颜色和样式：

* blue
* cyan
* faint
* green
* magenta
* red
* yellow


### 26.3. 文件输出 

默认情况下，Spring Boot仅记录到控制台，不写入日志文件。如果除了控制台输出之外还想写日志文件，则需要设置`logging.file`或`logging.path`属性（例如，在`application.properties`中）。

下表显示了`logging.*`属性如何一起使用：

|logging.file	|logging.path|例子|描述
|---|---|---|---
|(none)|(none)| |控制台输出日志
|Specific file|(none)|my.log|写入指定的日志文件。名称可以是确切的位置或相对于当前目录。
|(none)|具体目录|/var/log|将spring.log写入指定的目录。名称可以是确切的位置或相对于当前目录。

日志文件在达到10 MB时会旋转，并且与控制台输出一样，缺省情况下会记录ERROR级别，WARN级别和INFO级别的消息。可以使用`logging.file.max-size`属性更改大小限制。除非已设置`logging.file.max-history`属性，否则之前旋转的文件将被无限期地归档。

> 日志记录系统在应用程序生命周期的早期初始化。因此，通过`@PropertySource`注释加载的属性文件中找不到日志记录属性。

> 日志记录属性独立于实际的日志记录基础结构。因此，特定的配置键（例如Logback的`logback.configurationFile`）不受Spring Boot管理。

### 26.4. 日志级别 

所有支持的日志记录系统都可以使用logging.level在Spring Environment中设置日志级别（例如，在`application.properties`中）。`<logger-name>=<level>`其中level是TRACE，DEBUG，INFO， WARN，ERROR，FATAL或OFF。根记录器可以使用`logging.level.root`进行配置。

以下示例显示了application.properties中的潜在日志记录设置：

```
logging.level.root=WARN
logging.level.org.springframework.web=DEBUG
logging.level.org.hibernate=ERROR
```

### 26.5. 自定义日志配置 

可以通过在类路径中包含适当的库来激活各种日志记录系统，并且可以通过在类路径的根目录中或在以下Spring Environment属性指定的位置提供合适的配置文件来进一步进行自定义：`logging.config`。 您可以使用`org.springframework.boot.logging.LoggingSystem`系统属性强制Spring Boot使用特定的日志记录系统。该值应该是`LoggingSystem`实现的完全限定类名称。您还可以完全禁用Spring Boot的日志记录配置，方法是使用值none。

> 由于在创建`ApplicationContext`之前初始化日志记录，因此无法在Spring `@Configuration`文件中控制来自`@PropertySources`的日志记录。系统属性和传统的Spring Boot外部配置文件工作正常。）

根据您的日志记录系统，加载以下文件：

|日志系统|自定义
|---|---
| Logback | logback-spring.xml, logback-spring.groovy, logback.xml, or logback.groovy
| Log4j2 | log4j2-spring.xml or log4j2.xml
| JDK (Java Util Logging) | logging.properties

> 如果可能，我们建议您使用`-spring`变体进行日志记录配置（例如，`logback-spring.xml`而不是`logback.xml`）。如果您使用标准配置位置，则Spring无法完全控制日志初始化。

> Java Util Logging存在已知的类加载问题，当从“可执行jar”运行时会导致问题。如果可能的话，我们建议您从“可执行的jar”运行时避免它。

为了帮助定制，一些其他属性从Spring环境传输到系统属性，如下表所述：

|Spring Environment|System Property	| 注释
|---|---|---
|logging.exception-conversion-word|LOG_EXCEPTION_CONVERSION_WORD|记录异常时使用的转换字
|logging.file|LOG_FILE|如果已定义，则用于默认的日志配置。
|logging.file.max-size|LOG_FILE_MAX_SIZE|最大日志文件大小（如果启用LOG_FILE）。（仅支持默认的Logback设置。）
|logging.file.max-history|LOG_FILE_MAX_HISTORY|保留的归档日志文件的最大数量（如果启用LOG_FILE）（仅支持默认的Logback设置。）
|logging.path|LOG_PATH|如果已定义，则用于默认的日志配置。
|logging.pattern.console|CONSOLE_LOG_PATTERN|在控制台上使用的日志模式（stdout）。 （仅支持默认的Logback设置。）
|logging.pattern.dateformat|LOG_DATEFORMAT_PATTERN|日志日期格式的Appender模式（仅支持默认的Logback设置）
|logging.pattern.file|FILE_LOG_PATTERN|在文件中使用的日志模式（如果启用了LOG_FILE）（仅支持默认的Logback设置）
|logging.pattern.level|LOG_LEVEL_PATTERN|呈现日志级别时使用的格式（默认％5p）（仅支持默认的Logback设置）
|PID|PID|当前进程ID（如果可能，还没有定义为OS环境变量时发现）

所有支持的日志记录系统在分析其配置文件时都可以查阅系统属性。有关示例，请参阅spring-boot.jar中的默认配置：

* Logback
* Log4j2
* Java Util logging

> 如果您想在日志记录属性中使用占位符，则应该使用Spring Boot的语法，而不是基础框架的语法。值得注意的是，如果你使用Logback，你应该使用` : `作为属性名和默认值之间的分隔符，而不是使用`:-` 。

> 您可以通过仅覆盖`LOG_LEVEL_PATTERN`（或使用Logback的`logging.pattern.level`）来为日志行添加MDC和其他临时内容。例如，如果使用`logging.pattern.level = user：％X {user}％5p`，则默认日志格式包含“user”的MDC条目（如果存在），如以下示例中所示。

### 26.6. Logback扩展 

Spring Boot包含许多可用于高级配置的Logback扩展。你可以在你的`logback-spring.xml`配置文件中使用这些扩展。

> 由于标准logback.xml配置文件太早加载，因此无法在其中使用扩展名。您需要使用`logback-spring.xml`或定义`logging.config`属性。

> 这些扩展名不能用于Logback的配置扫描。如果尝试这样做，对配置文件进行更改会导致类似于以下记录之一的错误：

```
ERROR in ch.qos.logback.core.joran.spi.Interpreter@4:71 - no applicable action for [springProperty], current ElementPath is [[configuration][springProperty]]
ERROR in ch.qos.logback.core.joran.spi.Interpreter@4:71 - no applicable action for [springProfile], current ElementPath is [[configuration][springProfile]]
```

#### 26.6.1. 配置文件特定的配置 

使用`<springProfile>`标记可以根据活动的Spring配置文件选择性地包含或排除配置的各个部分。配置文件部分在`<configuration>`元素的任何位置都受支持。使用`name`属性指定哪个配置文件接受配置。多个配置文件可以用逗号分隔列表指定。以下清单显示了三个样本配置文件：

```xml
<springProfile name="staging">
	<!-- configuration to be enabled when the "staging" profile is active -->
</springProfile>

<springProfile name="dev, staging">
	<!-- configuration to be enabled when the "dev" or "staging" profiles are active -->
</springProfile>

<springProfile name="!production">
	<!-- configuration to be enabled when the "production" profile is not active -->
</springProfile>
```

#### 26.6.2. 环境属性

使用`<springProperty>`标签可以显示Spring环境中的属性以便在Logback中使用。如果要在Logback配置中访问`application.properties`文件中的值，那么这样做会很有用。标签的工作方式与Logback的标准`<property>`标签类似。但是，不是指定直接值，而是指定属性的来源（来自环境）。如果您需要将属性存储在本地范围以外的其他位置，则可以使用scope属性。如果您需要回退值（如果该属性未在环境中设置），则可以使用`defaultValue`属性。以下示例显示如何公开要在Logback中使用的属性：

```xml
<springProperty scope="context" name="fluentHost" source="myapp.fluentd.host"
		defaultValue="localhost"/>
<appender name="FLUENT" class="ch.qos.logback.more.appenders.DataFluentAppender">
	<remoteHost>${fluentHost}</remoteHost>
	...
</appender>
```

> 源代码必须在kebab格式中指定（例如`my.property-name`）。但是，可以使用宽松的规则将属性添加到环境中。

## 27.开发Web应用程序 

Spring Boot非常适合Web应用程序开发。您可以使用嵌入式Tomcat，Jetty，Undertow或Netty创建自包含的HTTP服务器。大多数Web应用程序都使用`spring-boot-starter-web`模块来快速启动和运行。您还可以选择使用`spring-boot-starter-webflux`模块构建反应性Web应用程序。

如果您尚未开发Spring Boot Web应用程序，则可以按照“Hello World！”进行操作。示例在入门部分。



### 27.1. Spring Web MVC框架

Spring Web MVC框架（通常简称为“Spring MVC”）是一个丰富的“模型视图控制器”Web框架。 Spring MVC允许您创建特殊的@Controller或@RestController bean来处理传入的HTTP请求。您的控制器中的方法通过使用@RequestMapping注释映射到HTTP。

以下代码显示了提供JSON数据的典型@RestController：

```java
@RestController
@RequestMapping(value="/users")
public class MyRestController {

	@RequestMapping(value="/{user}", method=RequestMethod.GET)
	public User getUser(@PathVariable Long user) {
		// ...
	}

	@RequestMapping(value="/{user}/customers", method=RequestMethod.GET)
	List<Customer> getUserCustomers(@PathVariable Long user) {
		// ...
	}

	@RequestMapping(value="/{user}", method=RequestMethod.DELETE)
	public User deleteUser(@PathVariable Long user) {
		// ...
	}

}
```

Spring MVC是核心Spring框架的一部分，详细信息参见参考文档。 spring.io/guides上还提供了几个涵盖Spring MVC的指南。

#### 27.1.1. Spring MVC自动配置 

Spring Boot为Spring MVC提供了自动配置，可与大多数应用程序配合使用。

自动配置会在Spring的默认设置之上添加以下功能：

* 包含`ContentNegotiatingViewResolver`和`BeanNameViewResolver` bean。
* 支持提供静态资源，包括对WebJars的支持（稍后在本文档中介绍））。
* 自动注册Converter，GenericConverter和Formatter bean。
* 支持HttpMessageConverters（稍后在本文档中介绍）。
* MessageCodesResolver的自动注册（稍后在本文档中介绍）。
* 静态index.html支持。
* 自定义Favicon支持（本文稍后会介绍）。
* 自动使用ConfigurableWebBindingInitializer bean（稍后在本文档中介绍）。

如果您想保留Spring Boot MVC功能，并且想要添加额外的MVC配置（拦截器，格式化器，视图控制器和其他功能），则可以添加自己的`@Configuration`类型`WebMvcConfigurer`，但不包含`@EnableWebMvc`。如果您希望提供`RequestMappingHandlerMapping`，`RequestMappingHandlerAdapter`或`ExceptionHandlerExceptionResolver`的自定义实例，则可以声明`WebMvcRegistrationsAdapter`实例以提供此类组件。

如果你想完全控制Spring MVC，你可以添加你自己的用`@EnableWebMvc`注解的`@Configuration`。

#### 27.1.2. HttpMessageConverters 

Spring MVC使用`HttpMessageConverter`接口来转换HTTP请求和响应。包装盒中包含明智的默认设置。例如，可以将对象自动转换为JSON（通过使用Jackson库）或XML（通过使用Jackson XML扩展（如果可用），或者如果Jackson XML扩展不可用，则通过使用JAXB）。默认情况下，字符串以UTF-8编码。

如果您需要添加或自定义转换器，则可以使用Spring Boot的HttpMessageConverters类，如下所示：

```java
import org.springframework.boot.autoconfigure.web.HttpMessageConverters;
import org.springframework.context.annotation.*;
import org.springframework.http.converter.*;

@Configuration
public class MyConfiguration {

	@Bean
	public HttpMessageConverters customConverters() {
		HttpMessageConverter<?> additional = ...
		HttpMessageConverter<?> another = ...
		return new HttpMessageConverters(additional, another);
	}

}
```

任何存在于上下文中的`HttpMessageConverter` bean都将添加到转换器列表中。您也可以用相同的方式覆盖默认转换器。

#### 27.1.3. 自定义JSON序列化器和反序列化器 

如果您使用Jackson来序列化和反序列化JSON数据，则可能需要编写自己的`JsonSerializer`和`JsonDeserializer`类。自定义序列化程序通常通过模块向杰克逊注册，但Spring Boot提供了另一种`@JsonComponent`注释，可以更容易地直接注册Spring Bean。

```java
import java.io.*;
import com.fasterxml.jackson.core.*;
import com.fasterxml.jackson.databind.*;
import org.springframework.boot.jackson.*;

@JsonComponent
public class Example {

	public static class Serializer extends JsonSerializer<SomeObject> {
		// ...
	}

	public static class Deserializer extends JsonDeserializer<SomeObject> {
		// ...
	}

}
```

`ApplicationContext`中的所有`@JsonComponent` bean都会自动在Jackson中注册。由于`@JsonComponent`是用`@Component`进行元注释的，因此通常的组件扫描规则适用。

Spring Boot还提供了`JsonObjectSerializer`和`JsonObjectDeserializer`基类，它们在序列化对象时为标准Jackson版本提供了有用的替代方法。有关详细信息，请参阅Javadoc中的`JsonObjectSerializer`和`JsonObjectDeserializer`。

#### 27.1.4. MessageCodesResolver

Spring MVC有一个策略来生成错误代码，用于从绑定错误中呈现错误消息：`MessageCodesResolver`。如果您设置了`spring.mvc.message-codes-resolver.format`属性`PREFIX_ERROR_CODE`或`POSTFIX_ERROR_CODE`，Spring Boot会为您创建一个（请参阅`DefaultMessageCodesResolver.Format`中的枚举）。

#### 27.1.5. 静态内容 

默认情况下，Spring Boot从类路径中的 `/static`（或 `/public`或 `/resources` 或 `/META-INF/resources`）目录或从`ServletContext`的根目录中提供静态内容。它使用Spring MVC中的`ResourceHttpRequestHandler`，以便您可以通过添加自己的`WebMvcConfigurer`并重写`addResourceHandlers`方法来修改该行为。

在独立的Web应用程序中，容器中的默认servlet也被启用并充当回退，如果Spring决定不处理它，则从`ServletContext`的根目录提供内容。大多数情况下，这不会发生（除非您修改默认的MVC配置），因为Spring始终可以通过`DispatcherServlet`处理请求。

默认情况下，资源映射到 `/**`，但您可以使用 `spring.mvc.static-path-pattern`属性对其进行调整。例如，将所有资源重定位到`/resources/**`可以实现如下：

```
spring.mvc.static-path-pattern=/resources/**
```
您还可以使用`spring.resources.static-locations`属性（用默认值替换目录位置列表）来自定义静态资源位置。根Servlet上下文路径`“/”`也会自动添加为位置。

除了前面提到的“标准”静态资源位置之外，还为Webjars内容制作了一个特例。如果以Webjars格式打包，那么在 `/webjars/**` 中具有路径的任何资源都将从jar文件提供。

> 如果您的应用程序打包为jar，请不要使用src / main / webapp目录。虽然这个目录是一个通用的标准，但它只适用于war包装，如果你生成一个jar包，它会被大多数构建工具默默地忽略。

Spring Boot还支持Spring MVC提供的高级资源处理功能，允许使用例如缓存清除静态资源或使用Webjars的版本不可知URL。

要为Webjars使用版本不可知的URL，请添加 `webjars-locator-core` 依赖项。然后声明你的Webjar。以jQuery为例，在`“/webjars/jquery/x.y.z/dist/jquery.min.js”`中添加`“/webjars/jquery/dist/jquery.min.js”`。其中x.y.z是Webjar版本。

> 如果您使用JBoss，则需要声明`webjars-locator-jboss-vfs`依赖项，而不是`webjars-locator-core`。否则，所有的Webjars将解析为404。

要使用缓存清除，以下配置为所有静态资源配置缓存清除解决方案，从而有效地在URL中添加内容哈希，如`<link href =“/ css / spring-2a2d595e6ed9a0b24f027f2b63b134d6.css”/>`

```
spring.resources.chain.strategy.content.enabled=true
spring.resources.chain.strategy.content.paths=/**
```

> 由于为Thymeleaf和FreeMarker自动配置了ResourceUrlEncodingFilter，因此资源链接将在运行时在模板中重写。使用JSP时，应该手动声明此过滤器。其他模板引擎目前不会自动支持，但可以使用自定义模板宏/助手和ResourceUrlProvider的使用。

例如，在使用JavaScript模块加载程序动态加载资源时，重命名文件不是一种选择。这就是为什么其他战略也得到支持并可以合并的原因。 “固定”策略在URL中添加静态版本字符串而不更改文件名，如以下示例所示：

```
spring.resources.chain.strategy.content.enabled=true
spring.resources.chain.strategy.content.paths=/**
spring.resources.chain.strategy.fixed.enabled=true
spring.resources.chain.strategy.fixed.paths=/js/lib/
spring.resources.chain.strategy.fixed.version=v12
```

通过该配置，位于`“/js/lib/”`下的JavaScript模块使用固定的版本控制策略（`“/v12/js/lib/mymodule.js”`），而其他资源仍然使用内容（<`link href =“/ CSS /弹簧2a2d595e6ed9a0b24f027f2b63b134d6.css“/>`）。 

请参阅ResourceProperties以获取更多支持的选项。

> 这个特性已经在专门的博客文章和Spring框架的参考文档中进行了详细描述。


#### 27.1.6. 欢迎页面 

Spring Boot支持静态和模板欢迎页面。它首先在配置的静态内容位置中查找index.html文件。如果找不到，它会查找索引模板。如果找到任何一个，它将自动用作应用程序的欢迎页面。

#### 27.1.7. 自定义Favicon 

Spring Boot会在配置的静态内容位置和类路径的根目录（按此顺序）中查找favicon.ico。如果存在这样的文件，它会自动用作应用程序的图标。

#### 27.1.8. 路径匹配和内容协商 

Spring MVC可以通过查看请求路径并将它匹配到应用程序中定义的映射（例如Controller方法上的@GetMapping注释），将传入的HTTP请求映射到处理程序。 

Spring Boot选择默认禁用后缀模式匹配，这意味着像“GET /projects/spring-boot.json”这样的请求不会与@GetMapping（“/projects/spring-boot”）映射匹配。这被认为是Spring MVC应用程序的最佳实践。此功能在过去对于没有发送正确的“Accept”请求标头的HTTP客户端来说非常有用;我们需要确保将正确的内容类型发送到客户端。如今，内容协商更可靠。 

还有其他方法可以处理不一致地发送适当的“Accept”请求标头的HTTP客户端。我们可以使用查询参数来确保诸如“GET /projects/spring-boot？format = json”的请求映射到@GetMapping（“/projects/spring-boot”），而不是使用后缀匹配。

```
spring.mvc.contentnegotiation.favor-parameter=true

# We can change the parameter name, which is "format" by default:
# spring.mvc.contentnegotiation.parameter-name=myparam

# We can also register additional file extensions/media types with:
spring.mvc.contentnegotiation.media-types.markdown=text/markdown
```

如果您了解注意事项并仍然希望应用程序使用后缀模式匹配，则需要进行以下配置：

```
spring.mvc.contentnegotiation.favor-path-extension=true

# You can also restrict that feature to known extensions only
# spring.mvc.pathmatch.use-registered-suffix-pattern=true

# We can also register additional file extensions/media types with:
# spring.mvc.contentnegotiation.media-types.adoc=text/asciidoc
```

#### 27.1.9. ConfigurableWebBindingInitializer 

Spring MVC使用`WebBindingInitializer`为特定请求初始化`WebDataBinder`。如果您创建自己的`ConfigurableWebBindingInitializer` `@Bean`，Spring Boot会自动配置Spring MVC以使用它。

#### 27.1.10. 模板引擎 

除了REST Web服务，您还可以使用Spring MVC为动态HTML内容提供服务。 Spring MVC支持各种模板技术，包括Thymeleaf，FreeMarker和JSP。另外，许多其他模板引擎还包括他们自己的Spring MVC集成。

Spring Boot包含以下模板引擎的自动配置支持：

* FreeMarker
* Groovy
* Thymeleaf
* Mustache

> 如果可能的话，应该避免使用JSP。将它们与嵌入式servlet容器一起使用时，存在几个已知的限制。

当您使用默认配置的模板引擎之一时，您的模板会从`src/main/resources/templates`中自动获取。

根据您运行应用程序的方式，IntelliJ IDEA以不同的方式排序类路径。使用主方法在IDE中运行应用程序会导致与使用`Maven`或`Gradle`或从其打包的jar运行应用程序时不同的顺序。这可能会导致Spring Boot无法在类路径中找到模板。如果您遇到此问题，可以在IDE中重新排序类路径，以便首先放置模块的类和资源。或者，您可以配置模板前缀以搜索类路径中的每个模板目录，如下所示：`classpath*:/templates/`。


#### 27.1.11. 错误处理 自定义错误页面 在Spring MVC之外映射错误页面 

默认情况下，Spring Boot提供了一个/错误映射，以合理的方式处理所有错误，并将其注册为servlet容器中的“全局”错误页面。对于机器客户端，它会生成一个JSON响应，其中包含错误，HTTP状态和异常消息的详细信息。对于浏览器客户端，有一个“whitelabel”错误视图，它以HTML格式呈现相同的数据（要对其进行自定义，添加可解决错误的View）。要完全替换默认行为，您可以实现ErrorController并注册该类型的bean定义或添加类型为ErrorAttributes的bean以使用现有机制，但替换内容。

> `BasicErrorController`可以用作自定义`ErrorController`的基类。如果您想为新的内容类型添加处理程序（默认情况下专门处理`text/html`并为其他所有内容提供回退），这一点特别有用。为此，请扩展`BasicErrorController`，添加一个带有`@RequestMapping`属性的公共方法，并创建一个新类型的bean。

您还可以定义一个用`@ControllerAdvice`注释的类来定制JSON文档以返回特定的控制器和/或异常类型，如以下示例所示：

```java
@ControllerAdvice(basePackageClasses = AcmeController.class)
public class AcmeControllerAdvice extends ResponseEntityExceptionHandler {

	@ExceptionHandler(YourException.class)
	@ResponseBody
	ResponseEntity<?> handleControllerException(HttpServletRequest request, Throwable ex) {
		HttpStatus status = getStatus(request);
		return new ResponseEntity<>(new CustomErrorType(status.value(), ex.getMessage()), status);
	}

	private HttpStatus getStatus(HttpServletRequest request) {
		Integer statusCode = (Integer) request.getAttribute("javax.servlet.error.status_code");
		if (statusCode == null) {
			return HttpStatus.INTERNAL_SERVER_ERROR;
		}
		return HttpStatus.valueOf(statusCode);
	}

}
```

在前面的示例中，如果由与AcmeController相同的包中定义的控制器抛出YourException，则将使用CustomErrorType POJO的JSON表示而不是ErrorAttributes表示形式。

#### 自定义错误页面

如果要为给定状态代码显示自定义HTML错误页面，则可以将文件添加到 /error 文件夹。错误页面可以是静态HTML（即，添加到任何静态资源文件夹下），也可以使用模板构建。文件的名称应该是确切的状态码或系列掩码。

例如，要将404映射到静态HTML文件，您的文件夹结构如下所示：

```
src/
 +- main/
     +- java/
     |   + <source code>
     +- resources/
         +- public/
             +- error/
             |   +- 404.html
             +- <other public assets>
```

要使用FreeMarker模板映射所有5xx错误，您的文件夹结构如下所示：

```
src/
 +- main/
     +- java/
     |   + <source code>
     +- resources/
         +- templates/
             +- error/
             |   +- 5xx.ftl
             +- <other templates>
```

对于更复杂的映射，您还可以添加实现ErrorViewResolver接口的Bean，如以下示例中所示：

```java
public class MyErrorViewResolver implements ErrorViewResolver {

	@Override
	public ModelAndView resolveErrorView(HttpServletRequest request,
			HttpStatus status, Map<String, Object> model) {
		// Use the request or status to optionally return a ModelAndView
		return ...
	}

}
```
您还可以使用常规的Spring MVC功能，例如`@ExceptionHandler`方法和`@ControllerAdvice`。 `ErrorController`然后拾取任何未处理的异常。

#### 在Spring MVC之外映射错误页面 

对于不使用Spring MVC的应用程序，您可以使用ErrorPageRegistrar接口直接注册ErrorPages。这个抽象直接与底层嵌入式servlet容器一起工作，即使你没有Spring MVC DispatcherServlet也可以工作。

```java
@Bean
public ErrorPageRegistrar errorPageRegistrar(){
	return new MyErrorPageRegistrar();
}

// ...

private static class MyErrorPageRegistrar implements ErrorPageRegistrar {

	@Override
	public void registerErrorPages(ErrorPageRegistry registry) {
		registry.addErrorPages(new ErrorPage(HttpStatus.BAD_REQUEST, "/400"));
	}

}
```

> 如果你注册了一个ErrorPage，并且这个路径最终由一个Filter来处理（就像一些非Spring的Web框架，比如Jersey和Wicket一样），那么过滤器必须被显式注册为一个ERROR调度器，如下面的例子：

```java
@Bean
public FilterRegistrationBean myFilter() {
	FilterRegistrationBean registration = new FilterRegistrationBean();
	registration.setFilter(new MyFilter());
	...
	registration.setDispatcherTypes(EnumSet.allOf(DispatcherType.class));
	return registration;
}
```

请注意，默认的`FilterRegistrationBean`不包含ERROR调度程序类型。 

小心：在部署到servlet容器时，Spring Boot使用其错误页面过滤器将具有错误状态的请求转发到适当的错误页面。如果响应尚未提交，则只能将请求转发到正确的错误页面。默认情况下，WebSphere Application Server 8.0和更高版本在成功完成servlet的服务方法后提交响应。您应该通过将`com.ibm.ws.webcontainer.invokeFlushAfterService`设置为false来禁用此行为。


#### 27.1.12. Spring HATEOAS 

如果您开发了一个使用超媒体的RESTful API，Spring Boot为Spring HATEOAS提供了自动配置，可与大多数应用程序配合使用。自动配置取代了使用`@EnableHypermediaSupport`并注册大量bean的需求，以便构建基于超媒体的应用程序，其中包括LinkDiscoverers（用于客户端支持）以及配置为将响应正确编组为所需表示形式的`ObjectMapper`。 `ObjectMapper`通过设置各种`spring.jackson.*`属性或`Jackson2ObjectMapperBuilder` bean（如果存在）来定制。

您可以使用@`EnableHypermediaSupport`来控制Spring HATEOAS的配置。请注意，这样做会禁用前面描述的ObjectMapper自定义。

非HATEOAS的响应例子是：

```javascript
GET /posts/1 HTTP/1.1
Connection: keep-alive
Host: blog.example.com
{
    "id" : 1,
    "body" : "My first blog post",
    "postdate" : "2015-05-30T21:41:12.650Z"
￼}
```

而HATEOAS的响应例子则是：

```javascript
{
    "id" : 1,
    "body" : "My first blog post",
    "postdate" : "2015-05-30T21:41:12.650Z",
    "links" : [
        {
            "rel" : "self",
            "href" : http://blog.example.com/posts/1,
            "method" : "GET"
        }
    ] 
}
```

#### 27.1.13. CORS支持 

跨源资源共享（CORS）是大多数浏览器实现的W3C规范，它允许您以灵活的方式指定授权哪种跨域请求，而不是使用诸如IFRAME或JSONP等安全性较低且功能较弱的方法。 

从4.2版开始，Spring MVC支持CORS。使用控制器方法在Spring Boot应用程序中使用@CrossOrigin标注的CORS配置不需要任何特定的配置。可以通过使用自定义addCorsMappings（CorsRegistry）方法注册WebMvcConfigurer bean来定义全局CORS配置，如下例所示：

```java

@Configuration
public class MyConfiguration {

	@Bean
	public WebMvcConfigurer corsConfigurer() {
		return new WebMvcConfigurer() {
			@Override
			public void addCorsMappings(CorsRegistry registry) {
				registry.addMapping("/api/**");
			}
		};
	}
}
```


### 27.2. Spring WebFlux框架

Spring WebFlux是Spring Framework 5.0中引入的新的反应式Web框架。与Spring MVC不同，它不需要Servlet API，完全异步和非阻塞，并通过Reactor项目实现Reactive Streams规范。 

Spring WebFlux有两种风格：基于功能和基于注释的。基于注释的注释非常接近Spring MVC模型，如以下示例所示：

```java
@RestController
@RequestMapping("/users")
public class MyRestController {

	@GetMapping("/{user}")
	public Mono<User> getUser(@PathVariable Long user) {
		// ...
	}

	@GetMapping("/{user}/customers")
	public Flux<Customer> getUserCustomers(@PathVariable Long user) {
		// ...
	}

	@DeleteMapping("/{user}")
	public Mono<User> deleteUser(@PathVariable Long user) {
		// ...
	}

}
```

功能变体“WebFlux.fn”将路由配置与请求的实际处理分开，如以下示例所示：

```java
@Configuration
public class RoutingConfiguration {

	@Bean
	public RouterFunction<ServerResponse> monoRouterFunction(UserHandler userHandler) {
		return route(GET("/{user}").and(accept(APPLICATION_JSON)), userHandler::getUser)
				.andRoute(GET("/{user}/customers").and(accept(APPLICATION_JSON)), userHandler::getUserCustomers)
				.andRoute(DELETE("/{user}").and(accept(APPLICATION_JSON)), userHandler::deleteUser);
	}

}

@Component
public class UserHandler {

	public Mono<ServerResponse> getUser(ServerRequest request) {
		// ...
	}

	public Mono<ServerResponse> getUserCustomers(ServerRequest request) {
		// ...
	}

	public Mono<ServerResponse> deleteUser(ServerRequest request) {
		// ...
	}
}
```

WebFlux是Spring框架的一部分，详细信息可在其参考文档中找到。

> 您可以根据需要定义任意数量的RouterFunction Bean，以模块化路由器的定义。如果您需要应用优先级，则可以定义Beans。


要开始，请将`spring-boot-starter-webflux`模块添加到您的应用程序中。

> 在您的应用程序中添加`spring-boot-starter-web`和`spring-boot-starter-webflux`模块会导致Spring Boot自动配置Spring MVC，而不是WebFlux。选择此行为是因为许多Spring开发人员将`spring-boot-starter-webflux`添加到他们的Spring MVC应用程序中以使用反应性WebClient。您仍然可以通过将选定的应用程序类型设置为`SpringApplication.setWebApplicationType（WebApplicationType.REACTIVE）`来实施您的选择。


#### 27.2.1. Spring WebFlux自动配置 

Spring Boot为Spring WebFlux提供了自动配置，可与大多数应用程序配合使用。 

自动配置会在Spring的默认设置之上添加以下功能： 

* 为HttpMessageReader和HttpMessageWriter实例配置编解码器（本文稍后介绍）。 
* 支持提供静态资源，包括对WebJars的支持（稍后在本文档中介绍）。 

如果您想保留Spring Boot WebFlux功能并且想要添加其他WebFlux配置，则可以添加您自己的`@Configuration`类型`WebFluxConfigurer`，但不包含`@EnableWebFlux`。 

如果你想完全控制Spring WebFlux，你可以添加你自己的用`@EnableWebFlux`注解的`@Configuration`。

#### 27.2.2. 使用HttpMessageReaders和HttpMessageWriters的HTTP编解码器 

Spring WebFlux使用HttpMessageReader和HttpMessageWriter接口来转换HTTP请求和响应。通过查看类路径中可用的库，它们使用CodecConfigurer配置为具有合理的默认值。 

Spring Boot通过使用`CodecCustomizer`实例进一步定制。例如，`spring.jackson.*` 配置键适用于Jackson编解码器。 

如果您需要添加或自定义编解码器，则可以创建一个自定义`CodecCustomizer`组件，如以下示例所示：

```java
import org.springframework.boot.web.codec.CodecCustomizer;

@Configuration
public class MyConfiguration {

	@Bean
	public CodecCustomizer myCodecCustomizer() {
		return codecConfigurer -> {
			// ...
		}
	}

}
```

您还可以利用Boot的自定义JSON序列化器和反序列化器。


#### 27.2.3. 静态内容 

默认情况下，Spring Boot将从类路径中的 /static（或 /public或 /resources或/ META-INF/resources）目录中提供静态内容。它使用Spring WebFlux中的ResourceWebHandler，以便您可以通过添加自己的WebFluxConfigurer并重写addResourceHandlers方法来修改该行为。 

默认情况下，资源映射到`/**`，但可以通过设置`spring.webflux.static-path-pattern`属性来调整资源。例如，将所有资源重定位到 `/resources/**`可以实现如下：

```
spring.webflux.static-path-pattern=/resources/**
```

您还可以使用`spring.resources.static-locations`来自定义静态资源位置。这样做会用目录位置列表替换默认值。如果这样做，默认的欢迎页面检测会切换到您的自定义位置。因此，如果您的任何位置在启动时都有index.html，那么它就是应用程序的主页。 

除了前面列出的“standard”静态资源位置之外，还为Webjars内容制作了一个特例。如果以Webjars格式打包，那么在 `/webjars/**` 中具有路径的任何资源都将从jar文件提供。

> Spring WebFlux应用程序不严格依赖于Servlet API，因此它们不能作为war文件进行部署，也不能使用 `src/main/webapp`目录。


#### 27.2.4. 模板引擎 

除了REST Web服务外，您还可以使用Spring WebFlux提供动态HTML内容。 Spring WebFlux支持各种模板技术，包括Thymeleaf，FreeMarker和Moustache。 

Spring Boot包含以下模板引擎的自动配置支持：

* FreeMarker
* Thymeleaf
* Mustache

当您使用默认配置的模板引擎之一时，您的模板会从 `src/main/resources/templates` 中自动获取。

#### 27.2.5. 错误处理 自定义错误页面 

Spring Boot提供了一个WebExceptionHandler，以合理的方式处理所有错误。它在处理顺序中的位置就在WebFlux提供的处理程序之前，这被认为是最后一个处理程序。对于机器客户端，它会生成一个JSON响应，其中包含错误，HTTP状态和异常消息的详细信息。对于浏览器客户端，有一个“whitelabel”错误处理程序，它以HTML格式呈现相同的数据。您也可以提供自己的HTML模板来显示错误（请参阅下一节）。

定制此功能的第一步通常涉及使用现有机制，但替换或增加错误内容。为此，您可以添加一个`ErrorAttributes`类型的bean。 

要更改错误处理行为，可以实现`ErrorWebExceptionHandler`并注册该类型的bean定义。因为`WebExceptionHandler`是相当低级的，所以Spring Boot还提供了一个便利的`AbstractErrorWebExceptionHandler`，让您以WebFlux功能的方式处理错误，如下例所示：

```java
public class CustomErrorWebExceptionHandler extends AbstractErrorWebExceptionHandler {

	// Define constructor here

	@Override
	protected RouterFunction<ServerResponse> getRoutingFunction(ErrorAttributes errorAttributes) {

		return RouterFunctions
				.route(aPredicate, aHandler)
				.andRoute(anotherPredicate, anotherHandler);
	}

}
```

要获得更完整的图片，您还可以直接继承`DefaultErrorWebExceptionHandler`并覆盖特定的方法。



#### 27.2.6. 网页过滤器 

### 27.3. JAX-RS 和 Jersey

### 27.4. 嵌入式Servlet容器支持 

#### 27.4.1. Servlet，过滤器和监听器 将Spring Servlet，过滤器和监听器注册为Spring Bean 

#### 27.4.2. Servlet上下文初始化 扫描Servlet，筛选器和侦听器 

#### 27.4.3. ServletWebServerApplicationContext 

#### 27.4.4. 定制嵌入式Servlet容器 程序化定制 直接自定义ConfigurableServletWebServerFactory 

#### 27.4.5. JSP限制

# 28. 安全 

## 28.1. MVC安全 

## 28.2. WebFlux安全 

## 28.3. OAuth2 

### 28.3.1. 客户端 

## 28.4. Actuator 安全 

### 28.4.1. 跨站请求伪造保护

## 29.使用SQL数据库 

### 29.1. 配置一个数据源 

#### 29.1.1. 嵌入数据库支持 

#### 29.1.2. 连接到生产数据库 

#### 29.1.3. 连接到JNDI数据源 

### 29.2. 使用JdbcTemplate 

### 29.3. JPA和“Spring Data” 

#### 29.3.1. 实体类 

#### 29.3.2. Spring Data JPA存储库 

#### 29.3.3. 创建和删除JPA数据库 

#### 29.3.4. 在View中打开EntityManager 

### 29.4. 使用H2的Web控制台 

#### 29.4.1. 更改H2 Console的路径 

### 29.5. 使用jOOQ 

#### 29.5.1. 代码生成 

#### 29.5.2. 使用DSLContext 

#### 29.5.3. jOOQ SQL方言 

#### 29.5.4. 定制jOOQ

## 30.使用 NoSQL 技术 


### 30.1. Redis 

#### 30.1.1. 连接到Redis 

### 30.2. MongoDB 
#### 30.2.1. 连接到MongoDB数据库 
#### 30.2.2. MongoTemplate 
#### 30.2.3. Spring Data MongoDB存储库 
#### 30.2.4. 嵌入式Mongo 

### 30.3. Neo4j 
#### 30.3.1. 连接到Neo4j数据库 
#### 30.3.2. 使用嵌入式模式 
#### 30.3.3. Neo4jSession 
#### 30.3.4. Spring Data Neo4j存储库 
#### 30.3.5. 存储库示例 

### 30.4. GemFire
 
### 30.5. Solr 
#### 30.5.1. 连接到Solr 
#### 30.5.2. Spring Data Solr存储库 

### 30.6. Elasticsearch 
#### 30.6.1. 使用Jest连接到Elasticsearch 
#### 30.6.2. 通过使用Spring Data 连接到Elasticsearch 
#### 30.6.3. Spring Data Elasticsearch存储库 

### 30.7. Cassandra
#### 30.7.1. 连接到Cassandra 
#### 30.7.2. Spring Data Cassandra存储库 

### 30.8. Couchbase 
#### 30.8.1. 连接到Couchbase 
#### 30.8.2. Spring Data Couchbase存储库 

### 30.9. LDAP 
#### 30.9.1. 连接到LDAP服务器 
#### 30.9.2. Spring数据LDAP存储库 
#### 30.9.3. 嵌入式内存LDAP服务器 

### 30.10. InfluxDB 
#### 30.10.1. 连接到InfluxDB

## 31.缓存 
### 31.1. 支持的缓存提供程序 
#### 31.1.1. 通用 
#### 31.1.2. JCache（JSR-107） 
#### 31.1.3. EhCache 2.x 
#### 31.1.4. Hazelcast 
#### 31.1.5. Infinispan
#### 31.1.6. Couchbase 
#### 31.1.7. Redis
#### 31.1.8. Caffeine
#### 31.1.9. Simple 
#### 31.1.10. None

## 32.信息 
### 32.1. JMS 
#### 32.1.1. ActiveMQ支持 
#### 32.1.2. Artemis支持 
#### 32.1.3. 使用JNDI ConnectionFactory 
#### 32.1.4. 发送消息 
#### 32.1.5. 接收消息 

### 32.2. AMQP 
#### 32.2.1. RabbitMQ支持 
#### 32.2.2. 发送消息 
#### 32.2.3. 接收消息 

### 32.3. Apache Kafka 
#### 32.3.1. 发送消息 
#### 32.3.2. 接收消息 
#### 32.3.3. 额外的 Kafka 属性

## 33.用RestTemplate调用REST服务 
### 33.1. RestTemplate自定义 

## 34.使用WebClient调用REST服务 
### 34.1. WebClient自定义 

## 35.验证 

## 36.发送电子邮件 

## 37.与JTA的分布式事务 
### 37.1. 使用Atomikos事务管理器 
### 37.2. 使用Bitronix事务管理器 
### 37.3. 使用Narayana事务管理器 
### 37.4. 使用Java EE托管事务管理器 
### 37.5. 混合XA和非XA JMS连接 
### 37.6. 支持替代嵌入式事务管理器


## 38. Hazelcast
## 39. Quartz Scheduler
## 40. Spring Integration
## 41. Spring Session
## 42. 监控和管理 JMX


## 43.测试 
### 43.1. 测试范围依赖关系 
### 43.2. 测试Spring应用程序 
### 43.3. 测试Spring Boot应用程序 
#### 43.3.1. 检测Web应用程序类型 
#### 43.3.2. 检测测试配置 
#### 43.3.3. 排除测试配置 
#### 43.3.4. 使用运行的服务器进行测试 
#### 43.3.5. Mocking 和 Spying Beans
#### 43.3.6. 自动配置的测试 
#### 43.3.7. 自动配置的JSON测试 
#### 43.3.8. 自动配置的Spring MVC测试 
#### 43.3.9. 自动配置的Spring WebFlux测试 
#### 43.3.10. 自动配置的数据JPA测试 
#### 43.3.11. 自动配置的JDBC测试 
#### 43.3.12. 自动配置的jOOQ测试 
#### 43.3.13. 自动配置的数据MongoDB测试 
#### 43.3.14. 自动配置的数据Neo4j测试 
#### 43.3.15. 自动配置的数据Redis测试 
#### 43.3.16. 自动配置的数据LDAP测试 
#### 43.3.17. 自动配置的REST客户端 
#### 43.3.18. 自动配置的Spring REST Docs测试 自动配置的Spring REST Docs使用Mock MVC进行测试 自动配置的Spring REST Docs使用REST Assured进行测试 
#### 43.3.19. 用户配置和切片 
#### 43.3.20. 使用Spock测试Spring Boot应用程序 

### 43.4. 测试工具 
#### 43.4.1. ConfigFileApplicationContextInitializer 
#### 43.4.2. EnvironmentTestUtils 
#### 43.4.3. OutputCapture 
#### 43.4.4. TestRestTemplate

## 44. Web Sockets
## 45. Web Services