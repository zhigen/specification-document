<a id="language"></a>
简体中文 | [English](/readme/README.en-US.md)

<a id="title"></a>
# 自述文件编写规范及模版
<a id="introduction"></a>
本项目使用自述文件的方式，总结了自述文件的编写规范，同时作为自述文件示例。

<a id="logo"></a>
![logo](/static/logo.png "logo tip")

<a id="badge"></a>
[![badge](https://img.shields.io/badge/label-message-blue)](https://shields.io/)

<a id="contents"></a>
# 目录
* [1. 组成部分](#1)
    * [1.1. 国际化](#11)
    * [1.2. 项目概述](#12)
    * [1.3. 项目目录](#13)
    * [1.4. 项目背景](#14)
    * [1.5. 安装](#15)
    * [1.6. 配置](#16)
    * [1.7. 使用](#17)
    * [1.8. 示例](#18)
    * [1.9. 相关项目](#19)
    * [1.10. 维护者](#1a)
    * [1.11. 贡献者](#1b)
    * [1.12. 贡献](#1c)
    * [1.13. 许可证](#1d)
* [2. 语法](#2)
    * [2.1. 链接](#21)
    * [2.2. 标题](#22)
    * [2.3. 图片](#23)
    * [2.4. 徽章](#24)
    * [2.5. 列表](#25)
    * [2.6. 锚点](#26)
    * [2.7. 引用](#27)
    * [2.8. 代码块](#28)
    * [2.9. 其他](#29)

<a id="1"></a>
## 1. 组成部分
标准的自述文件，大概有以下几部分组成：

<a id="11"></a>
### 1.1. 国际化
项目不要局限于母语文档，建议写成多语言的自述文件，让来自全球的人都能更方便的了解你的项目。<br/>
[示例](#language)<br/>
示例代码：

    简体中文 | [English](/readme/README.en-US.md)

<a id="12"></a>
### 1.2. 项目概述
项目概述能让别人快速的了解项目。概述内容通常有以下几点：
* 项目名称<br/>
    [示例](#title)<br/>
    示例代码：<br/>

        # 自述文件编写规范及模版

* 项目简介<br/>
    [示例](#introduction)

* 项目logo<br/>
    [示例](#logo)<br/>
    示例代码：<br/>

        ![logo](/static/logo.png "logo tip")

* 项目徽章<br/>
    [示例](#badge)<br/>
    示例代码：<br/>

        [![badge](https://img.shields.io/badge/label-message-blue)](https://shields.io/)

<a id="13"></a>
### 1.3. 项目目录
目录有助于查阅有关资料。<br/>
[示例](#contents)<br/>
示例部分代码：<br/>

    * [1 组成部分](#1)

<a id="14"></a>
### 1.4. 项目背景
描述项目存在的意义，产生的背景。如：<br/>
有好的自述文件的项目不一定是一个好项目，但一个好项目一定有一个好的自述文件。自述文件写得好能减少很多使用成本，能帮助这个项目让更多人了解，更多人使用。

<a id="15"></a>
### 1.5. 安装
说明项目的安装方式。如：<br/>

    $ git clone https://github.com/zhigen/specification-document.git

<a id="16"></a>
### 1.6. 配置
说明项目需要进行的配置操作。

<a id="17"></a>
### 1.7. 使用
说明项目的使用方法。

<a id="18"></a>
### 1.8. 示例
项目的使用示例。<br/>
[example](#language)

<a id="19"></a>
### 1.9. 相关项目
与本项目相关的项目。<br/>
[JAVA开发规范](../java/README.md)

<a id="1a"></a>
### 1.10. 维护者
项目的主要维护者。<br/>
[@zhigen](https://github.com/zhigen)

<a id="1b"></a>
### 1.11. 贡献者
列出对此项目有贡献的人。<br/>
[@zhigen](https://github.com/zhigen)

<a id="1c"></a>
### 1.12. 贡献
提供参与贡献的方式。<br/>
[Pull Request](https://github.com/zhigen/specification-document/pulls)

<a id="1d"></a>
### 1.13. 许可证
声明本项目的许可证。步骤：<br/>
项目内增加LICENSE文件，然后在自述文件许可证部分给出链接
[WTFPL](/LICENSE) © Lu Zhigen

<a id="2"></a>
## 2. 语法
自述文件常用的语法主要有：

<a id="21"></a>
### 2.1. 链接
    [label](url)
label为链接显示文字，url为链接地址，链接地址可用绝对或相对路径或锚点

<a id="22"></a>
### 2.2. 标题
    # 标题
\#+空格+标题，\#到\######分别对应1到6级标题

<a id="23"></a>
### 2.3. 图片
    ![alt](src "tip")
alt为图片替代文字，src为图片地址，图片地址可用绝对或相对路径，tip为鼠标悬停文字

<a id="24"></a>
### 2.4. 徽章
    [![alt](https://img.shields.io/badge/label-message-color)](https://shields.io)
徽章也是图片，只是加上了链接。通过shields.io生成徽章，label为前部分文字，message为后半部文字，color为后半部颜色。详细可了解：https://shields.io

<a id="25"></a>
### 2.5. 列表
    * a
      * b
        * c
星号加空格为一级列表，二级则在前面增加2个空格即可

<a id="26"></a>
### 2.6. 锚点
    <a id="1"></a>
通过id定义锚点，链接通过(#id)方式跳转至锚点

<a id="27"></a>
### 2.7. 引用
    > 引用
通过\>标识内容为引用，多个\>会将引用内容分成多级

<a id="28"></a>
### 2.8. 代码块
    ```markdown
    
    ```
通过三个反引号，加上语言类型，可将包括代码以对应语言显示

<a id="29"></a>
### 2.9. 其他
    \
通过反斜线可将转义字符输入。<br/>
\`\#\>