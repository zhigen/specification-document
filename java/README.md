简体中文 | [English](/java/README.en-US.md)

# JAVA开发规范
由于JAVA语言已有成熟的编码规范，我们使用现成的就好了。

![logo](/static/logo.png "logo tip")

[![badge](https://img.shields.io/badge/license-WTFPL-blue)](http://www.wtfpl.net/)

# 目录
* [1. 阿里规范](#1)
    * [1.1. 安装步骤](#11)
    * [1.2. 使用方法](#12)    
* [2. SonarLint规范](#2)
    * [2.1. 安装步骤](#21)
    * [2.2. 使用方法](#22)

<a id="1"></a>
## 1. 阿里规范
> 阿里巴巴集团推出的《Java开发手册》是阿里巴巴近万名开发同学集体智慧的结晶，以开发视角为中心，详细列举如何开发更加高效、更加容错、更加有协作性，力求知其然，更知其不然，结合正反例，让Java开发者能够提升协作效率、提高代码质量。

<a id="11"></a>
### 1.1. 安装步骤
* 在线安装

        idea->Settings->Plugins->Marketplace->搜索Alibaba Java Coding Guidelines->Install->重启

* 硬盘安装<br/>
    [官方插件](https://plugins.jetbrains.com/plugin/10046-alibaba-java-coding-guidelines)

        idea->Settings->Plugins->Settings->Install Plugin From Disk...

<a id="12"></a>
### 1.2. 使用方法
    idea->检测对象->右键->编码规约扫描->根据检测结果修改代码

<a id="2"></a>
## 2. SonarLint规范
> SonarLint是一个免费的IDE扩展，可让您在编写代码时修复错误和漏洞！像拼写检查器一样，SonarLint可以即时突出显示编码问题，并提供清晰的修复指导，以便您甚至在提交代码之前就可以解决它们。在流行的IDE（Eclipse，IntelliJ，Visual Studio，VS Code）和流行的编程语言中，SonarLint帮助所有开发人员编写更好，更安全的代码！

<a id="21"></a>
### 2.1. 安装步骤
* 在线安装<br/>
    参考[1.1. 安装步骤](#11)，搜索词为SonarLint

* 硬盘安装<br/>
    [官方插件](https://plugins.jetbrains.com/plugin/7973-sonarlint)

        idea->Settings->Plugins->Settings->Install Plugin From Disk...

<a id="22"></a>
### 2.2. 使用方法
    idea->检测对象->右键->SonarLint->Analyze with SonarLint