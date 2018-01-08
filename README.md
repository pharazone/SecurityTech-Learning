# SecurityTech-Learning

Copyright (c) 2018 HFBB All Rights Reserved.

## 安全技术学习计划（初稿Ver0.1）

## 一.Web安全
### 1.准备工作
- 了解什么是安全，安全的作用和目的是什么。

- 当前掌握的计算机水平，是否了解基本的计算机操作和常用软件使用能力，是否了解计算机，服务器，脚本等，是否了解几门常用语言。

- 对于目前业界存在的安全漏洞的了解。

- 阅读安全相关书籍和关注安全界名人博客来系统的学习理论知识。

### 2.安全知识基础的学习
- 互联网基础协议的学习，例如**七层模型，http协议和https协议，ssh协议，SSL协议等**。通过了解安全协议来理解传输过程中的安全机制，对于今后的学习将会起到巩固作用。

- 理解业界常规漏洞，阅读**OWASP TOP 10**，学习常见漏洞的知识，搞清楚原理和漏洞的产生场景，分析漏洞的危害。

- 自我进行最基础的Hack练习，通过在OWASP TOP 10中了解到的基本漏洞，来进行最基础的训练，通过最基础的黑入练习来进行实际操作，切身感受漏洞形成的原因，状态以及解决方案。推荐平台：**DVWA,XVWA,WebGoat**.

- 掌握工具的使用。安全工具的掌握能给安全测试带来事半功倍的效果，目前主流的安全工具有以下几类:
  > **Burp Suite** 代理拦截工具，拥有诸多模块
  >
  > **Fiddler** 代理拦截工具
  >
  > **Sqlmap** Sql自动化注入工具
  >
  > **Namp** 端口扫描工具

- 脚本语言和编程语言的了解。对于漏洞来说，有时候代码中的漏洞是很难发觉，这时候就需要**白盒测试，审计代码**。

### 3.安全技术的进阶

- **思考原理**。了解一个漏洞是怎么样形成的，最主要的还是去理解它产生的原理，这时候就需要利用之前掌握的理论知识和实战经验，对该漏洞的触发做出分析。

- 学习**数据库，服务器**相关的知识，明确服务器和数据库的使用框架，从更深层次理解Web安全和服务器之间的联系。
  - 常见服务器的种类

  - 常见数据库的种类

- **正则表达式** 从理解正则表达式入手，明确学习目的，掌握正则表达式的基本语法和调试工具的使用。

- **Python/PHP/JAVA** 语言的学习，从基本语法入手，尤其是Python，可以运用Python强大的库自己写一些网络小工具，如爬虫

- **漏洞平台**，亲自去参与漏洞平台众测任务，实际感受漏洞的挖掘。从平台上找出漏洞的分析方法去理解并试着分析。

- 良好而高效的习惯，**VIM，Markdown语法，Git，OneNote，印象笔记，Linux，Bash命令行** 等。作为技术工程师，一个高效的习惯可能会带来高效率的工作以及高效率的生活状态。

## 二.移动安全
### 1.移动安全基础
- 移动安全的基本概念的了解，包括安卓和iOS平台的机制。

- 理解安卓平台内核机制，从底层到应用层，从组件到包结构构成，包括但不限于APP的编译和反编译，动态调试，反编译代码等。具体安卓端常见漏洞的学习可以参考[OWASP Mobile Top 10 2016](https://www.owasp.org/index.php/Mobile_Top_10_2016-Top_10)

- 理解iOS平台的机制，从基础入手，包括但不限于：IPA包的解压和反编译，动态调试代码，参看打印日志等方面。

### 2.移动安全相关工具

>**apktool** APK的编译和反编译工具

>**a**
