---
layout: post
title: "Python笔记"     # 文章标题
date:  2024-12-17 0:31:47 +0800
categories: jekyll update
---

#北理 Python语言程序设计笔记

1946-1981 计算机系统结构时代 计算能力问题（C语言）

1981-2008 网络和视窗时代 交互问题（Java）

2008-2016 复杂信息系统时代 数据问题（Python）

2017-     人工智能时代 人类的问题



Python

学习内容：编程逻辑，第三方库

语言本质：理解问题求解

解决问题：各类问题

适用对象：所有专业

Python语言是计算机时代演进的结果



Python语言的特点：**通用语言**，可以用于普适计算求解的开发，并不局限于某一门类的应用。

Python优势：

强制可读性

较少的底层语法元素

多种编程方式

**支持中文字符**

C代码量的10%（语法简洁）

拥有>13万第三方库（生态高产）



C/C++：python归python，C归C，偏向底层开发

Java：针对特定开发和岗位需求

HTML/CSS/JS：不可替代的**前端技术**，全栈能力



Python是最高产的程序语言

是掌握抽象并求解计算问题综合能力的语言

是了解产业界解决复杂计算问题方法的语言



编程语言的种类

机器语言：一种二进制语言，直接使用二进制代码表达指令，计算机硬件（CPU）可以直接执行，与具体CPU型号有关。

汇编语言：一种将二进制代码直接对应助记符的编程语言。汇编语言与CPU型号有关，程序不通用，需要编译器转换。

高级语言：更接近自然语言，同时更容易描述计算问题。高级语言与具体CPU型号无关，编译后运行。

总结：

**机器语言：代码直接执行，与CPU型号有关**

**汇编语言：有助记符，汇编器，与CPU型号有关**

**高级语言：接近自然语言，编译器，与CPU型号无关。**



- **Turtle库（Python标准库）**

Python计算生态=标准库+第三方库

标准库：随解释器直接安装到操作系统中的功能模块

第三方库：需要经过安装才能使用的功能模块

库Library , 包Package , 模块Module，统称**模块**



- **RGB色彩模式**

由三种颜色构成的万物色。RGB指红绿蓝三个通道的颜色组合，覆盖视力所能感知的所有颜色。

RGB每色取值范围0-255整数或0-1小数



- **库引用**：扩充Python程序功能的方式

使用import保留字完成，采用<a>.<b>()编码风格 。

可使用from和import共同实现对库的引用。

![img](https://i1.hdslb.com/bfs/note/308bec56925f2921e5169b38a7e89190e4143f12.jpg@1192w.webp)

也可使用import和as保留字共同完成对库的引用。

![img](https://i1.hdslb.com/bfs/note/3e625636becf49b7ba28bef03eb69a06de6231e5.jpg@1192w.webp)



- **循环语句与range()函数**

循环语句指按照一定次数循环执行一组语句。

在Python基本语法体系中，range()函数最主要作用是与 for,in搭配形成计数循环。



- **第二章主要语法内容**

![img](https://i1.hdslb.com/bfs/note/e655faa20efd85a377a825c9190322a4b6dfff0c.jpg@1192w.webp)



- **第三章 基本数据类型**

方法论：Python语言数字及字符串类型

实践能力：初步学会编程进行字符类操作

**整数类型**与数学中整数的概念一致

![img](https://i1.hdslb.com/bfs/note/8738ab54525918f8457c73573985592e3cd677e5.jpg@1192w.webp)

**浮点类型**与数学中实数的概念一致

![img](https://i1.hdslb.com/bfs/note/df21d08f16b3c2d722f694e1d2ccd6064cf4bcd2.jpg@1192w.webp)

浮点数间运算存在不确定尾数，不是bug。

二进制表示小数可以无限接近，但不完全相同。

为了解决浮点数间运算存在的尾数问题，可以使用round()函数。

![img](https://i1.hdslb.com/bfs/note/b58d46e6d8127158fcc8b04a8529be4874072b0b.jpg@1192w.webp)

浮点数可以采用科学计数法表示

![img](https://i1.hdslb.com/bfs/note/edf74af0444581f5e21c96fcbc460b1aab14ec5c.jpg@1192w.webp)



在众多语言中，只有Python语言提供了**复数类型。**

复数类型与数学中的复数概念是一致的。

复数类型在常规计算机编程中很少使用，它却是进行空间变换，尤其是跟复变函数相关的科学体系中最常用的一种类型。

- **数值运算操作符**

操作符是完成运算的一种符号体系，Python借鉴了许多数学中的操作符进行数学运算。

![img](https://i1.hdslb.com/bfs/note/a1c72c56cf17ca624642dbdacd6bf53308ea31a4.jpg@1192w.webp)



![img](https://i1.hdslb.com/bfs/note/0147ee1569023f24826076c9f558a7e31efe478d.jpg@1192w.webp)

不同的数字类型间可以进行混合运算

类型间可进行混合运算，生成结构为“最宽”类型

三种类型存在一种逐渐“扩展”或“变宽”的关系：

整数是浮点数的特殊形式，浮点数是复数的特殊形式

如（整数+浮点数=浮点数）

- **数值运算函数**

Python提供了一些以内置函数形式来完成的数值运算功能

![img](https://i1.hdslb.com/bfs/note/9438dbf9dd8d04aa6052c6ee9527007eb6973202.jpg@1192w.webp)



![img](https://i1.hdslb.com/bfs/note/ed89a7d04eb06c172c73f919ddbafb3b89404c57.jpg@1192w.webp)

![img](https://i1.hdslb.com/bfs/note/31c37fc6b8271bee5b580dc1d3d896f971eb9c34.jpg@1192w.webp)