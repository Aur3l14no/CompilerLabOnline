# CompilerLabOnline

## Demo
http://139.199.104.107:4000/

## 第一次实验

#### 实验目的
加深对词法分析原理的理解，掌握编写简单词法分析程序的一般步骤。

#### 实验步骤
1. 分析所给的PL0文法，确定关键字，分界符，运算符，常量。
2. 设计词法分析器代码。
3. 完善出错处理、输入输出。
4. 用flask框架搭个站用于展示。

#### 实验感想
加深了对词法分析原理的理解
1. 词法分析时往往需要在两种单词之间选择，它的规则可概括为选更长和更优先的那个。理解了这一点就容易设计代码了。
2. 词法分析的本质是利用多个正则表达式去匹配文本。