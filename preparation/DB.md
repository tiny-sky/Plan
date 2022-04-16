# 数据库

> 数据库是结构化信息或数据（一般以电子形式存储在计算机系统中）的有组织的集合，通常由数据库管理系统 (DBMS) 来控制。在现实中，数据、DBMS 及关联应用一起被称为数据库系统，通常简称为数据库。

众所周知 ，程序就是通过算法处理数据，然后达到某些预期的效果的方式。

数据库最早于  1960年诞生，经过长时间的发展，现在已经非常专业和成熟了。现在软件开发也从之前的 自己处理和管理数据 变成了 交由专业的数据库管理系统进行管理，程序只负责与数据库管理系统进行交互，简化软件开发的复杂度。

## 怎么学习数据库呢？

数据库 是 分为两部分进行学习的。

第一部分，学习 `SQL语句(结构化查询语言)`  , 这是任何想要使用数据库的应用程序比须了解和掌握的。数据库管理系统通过处理 SQL语句，在内部进行数据的处理，最后将结果以某种形式返回，我们开发的应用如果需要使用数据库，就应该了解和掌握 SQL语句的使用。

第二部分，了解数据库管理系统的内部运行。既然数据库用起来这么方便，那么它是怎么做到的呢？


### SQL 基础入门

#### 书籍推荐

《mysql 必知必会》
《MySQL 是怎样运行的：从根儿上理解 MySQL》
《MySQL技术内幕：InnoDB存储引擎》

关系型数据库和非关系型数据库都可
待补充

> 第一本书，mysql必知必会，阅读时长大概1周。 了解关系型数据库的一些基本概念，和基本的sql语句的使用。完了之后可以做到----按照自己需求创建数据库，拼写增删改查 的语句。  （题外话：再学一下c语言操作mysql的api，就可以完成在c语言程序中使用数据库）

#### 任务说明


-  `GNU/Linux` 操作系统下安装下安装  任意关系型数据库，包括配置创建普通用户和管理操作权限 （不用记，走一遍流程就大概知道要先干什么在干什么）

- 学会 `SQL` 基本语法（`CRUD`）----- mysql必知必会 讲的挺详细的，要实践操作



### 数据库的运行

必备知识  




#### 书籍推荐

> 第二本书，[MySQL 是怎样运行的：从根儿上理解 MySQL](https://juejin.cn/book/6844733769996304392) 。这个可以大二想好好学一学数据库的时候看，算是一个过度书，讲的比必知必会深入些，但是语言通俗易懂，好理解，可以为下来的数据库原理的学习打基础。

> 第三本书，innodb技术内幕。还没看，待补充，听说很好。

> 还有  帆船书，高性能mysql ，等  

> 分布式相关有  ----- DDIA  


#### 课程推荐

- `cmu 15445`  数据库系统设计：CMU的神课，是讲数据库底层原理的课程，是在CMU开发的一个供教学的数据库系统bustub上面添加更多功能的支持。如果你想深入数据库的底层，那么这门课非常适合你。即便你以后做的是后台开发，了解数据库底层原理也对你大有裨益。Andy Pavlo也是数据库领域非常有名的教授，课堂效果很好。
- `UCB CS186: Introduction to Database System`

#### 任务推荐

如果你想正式学习数据库的话，建议按照这个培养方案来完成。
[DSCLab 新生培养计划](https://github.com/CDDSCLab/training-plan)