## Python核心编程

### 第一章 欢迎来到python世界

#### 特点
##### Python支持面向对象
把一组数据结构和处理它们的方法组成对象(object)，把相同行为的对象归纳为类(class)，通过类的封装(encapsulation)隐藏内部细节，
通过继承(inheritance)实现类的特化(specialization)／泛化(generalization)，
通过多态(polymorphism)实现基于对象类型的动态分派(dynamic dispatch).

##### 易读易学易维护
##### 自带gc

#### Python与其他语言比较
+ 比Perl简洁易用
+ 比Java简洁，更容易快速上手

### 第二章 快速入门
+ raw_input输入为字符串, 若需要转化为整形，则`int(raw_input())`
+ Python不支持i++，++i等
+ Python有五种基本数字类型，`int long bool float complex`
+ 第一个字符串的索引是0，最后一个字符串的索引是-1

### 第三章 Python基础
在Python语言中，对象是通过引用传递的。在赋值时，是将该对象的引用而不是值赋值给变量。

### 第四章 Python对象
Python对象都拥有三个特征：身份，类型和值。
+ 身份：每个对象都有一个唯一的身份标识自己，任何对象的身份可以使用内建函数`id()`来得到。这个值可以被认为是该对象的内存地址
+ 类型：对象的类型决定了该对象可以保存什么类型的值，可以进行什么样的操作。使用内建函数`type()`可以查看Python对象的类型
+ 值：对象表示的数据项

Python不支持方法或者函数的重载。

可变类型： 列表(list)、字典(dict)

不可变类型：数字(int)、字符串(str)、元组(tuple)


### 第五章 数字
+ Python有五种基本数字类型，`int long bool float complex`
+ 布尔型： True & False
+ 标准整形：跟机器的位数相同，即32bit机器上为32位，在64bit机器上为64位
+ 长整形：在值后面加上字母L即可得到长整形
+ 双精度浮点型：对应C语言里面的double类型
+ 复数：`1+2j`


### 第六章 序列：字符串、列表和元组

#### 序列(list)
+ `seq[ind]`          获得下标为ind的元素
+ `seq[ind1:ind2]`    获得下标从ind1到ind2间的元素
+ `seq * expr`        序列重复expr次
+ `seq1 + seq2`       连接序列seq1和seq2
+ `obj in seq`        判断obj元素是否包含在seq中
+ `obj not in seq`    判断obj元素是否不包含在seq中
