# 什么是变量

变量的定义是： 用来命名一个数据的标识符。



# 变量的类型

一个变量的类型，决定了该变量可以包含什么样的值。
Java中有八种基本类型，都是Java语言预先定义好的，并且是关键字。

这八种基本类型分别是：
整型     （4种）
字符型 （1种）
浮点型 （2种）
布尔型 （1种）

<center>图1 基本数据类型</center>

![基本数据类型](https://i.ibb.co/ZBFnt2s/image.png)





<center>图2 基本数据类型的取值范围</center>

![image](https://i.ibb.co/KyC0dhP/image.gif)



# 实例

```java
//整型
byte b = 1;
short s = 200;
int i = 300;
long l = 400;

//如果试图给byte类型的变量赋予超出其范围的值，就会产生编译错误
//byte b2 = 200;

//字符型
char c = '中';
//char 只能存放一个字符，超过一个字符就会产生编译错误
//char c2 = '中国'; //报错
//char c3 = 'ab'; //报错


//浮点型
/*浮点数类型有两种
float 长度为32位
double 长度为64位
注意： 默认的小数值是double类型的
所以 float f = 54.321会出现编译错误，因为54.321的默认类型是 double，其类型 长度为64，超过了float的长度32
在数字后面加一个字母f，直接把该数字声明成float类型
float f2 = 54.321f,
这样就不会出错了*/


//布尔型
boolean b1 = true;
boolean b2 = false;

// 虽然布尔型真正存放的数据是0(false) 1(true)
// 但是，不能直接使用0 1 进行赋值
//boolean b3 = 1;
```