---
title: 'ES6'
date: 2018-09-22 13:14:36
tags:
- es6
- js
categories:
- 前端
---

#### ES6学习笔记

##### <u>1.    let，const命令</u>

​	ES5中只有2个作用域：全局作用域，函数作用域。

​	ES6中增加了块级作用域：{ }包裹的区域。

###### <u>1.1 let</u>

​		只在当前块作用域有效，在外可理解为不存在。

​		let不能重复声明同一个变量。

###### <u>1.2 const</u>

​	声明的时候必须赋值。

​	定义常量，一般声明后不可更改，

​	*特殊情况： 

```javascript
const a = {
    k: 1,
    m: 2
}
a.b = 3
console.log(a) // {k:1, m: 2, b:3} 
//因为对象是引用类型， const存储的是指针，指针一直没有改变，改变的是指针指向的对象
```

##### <u>2.     结构赋值</u>

​	2.1 分类

|  数组结构赋值  |   对象结构赋值   | 字符串结构赋值 |
| :------------: | :--------------: | :------------: |
| 布尔值结构赋值 | 函数参数结构赋值 |  数值结构赋值  |

​		参考 https://www.cnblogs.com/imwtr/p/5893814.html

##### <u>3.     正则扩展</u>

##### <u>4.     字符串扩展</u>

##### <u>5.     数字扩展</u>

##### <u>6.     数组扩展</u>

##### <u>7.     函数扩展</u>

##### <u>8.     对象扩展</u>

##### <u>9.     Symbol用法</u>

##### <u>10.  set，map数据结构</u>

##### <u>11.  set，map与数组，对象的对比</u>

##### <u>12.  proxy和reflect</u>

##### <u>13.  类与对象</u>

##### <u>14.  Promise</u>

##### <u>15.  Iterator</u>

##### <u>16.  Generator</u>

##### <u>17.  Decorators</u>

##### <u>18.  Module模块化</u>

