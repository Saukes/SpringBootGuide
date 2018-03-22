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
