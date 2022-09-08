# C++ 结构

本文为C++ primer plus第六版学习笔记 -- 001 -----------会持续更新

同时部分借鉴[C++ 数据结构 | 菜鸟教程 (runoob.com)](https://www.runoob.com/cplusplus/cpp-data-structures.html)

## 结构简介

可以将不同类型（如int float）储存在一个单元中的数据结构 （OOP思想：面向对象程序设计）

**结构声明**

`struct type_name` 

`{ member_type1 member_name1;` 

  `member_type2 member_name2;` 

  `member_type3 member_name3;` 

  `. .` 

`} ;`

## 

注：member_type 同样可以是string

定义结构之后，就可以创建这种类型的变量了：

`type_name  object; //不需要声明关键字 struct`

可以通过 “ ." 来访问各个成员：

`object.member_name1`



<u>结构声明的位置：</u>

1. 外部声明：可以被其后面任何函数使用（提倡）
2. 内部声明：只能被该声明所属的函数使用



**结构初始化**

`type_name object =`

`{`

`"basketball", //member_name1 value`

`1.88, // member_name2 value`

`29.99// member_name3 value`

`}`

也可以放在同一行中，但以逗号隔开。



**结构赋值**

可以用（=）将结构赋给另一个同类型的结构

