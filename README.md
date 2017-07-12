# frontend-interview-2017

## Table of Content

* [HTML/CSS](#HTML/CSS)
* [JavaScript](#JavaScript)
* [Others](#Others)

## HTML / CSS

1. 圣杯布局、双飞翼布局、两栏布局
2. 栅格系统（Bootstrap的实现方式）
3. CSS盒模型（两种盒模型如何相互转换）
4. 浮动（清除浮动）
5. BFC（如何触发？BFC用于解决的问题）
6. 浮动与清除浮动
7. BEM / OOCSS
8. 垂直居中
9. CSS 3有哪些特性
10. transform、transition、animate有何区别
11. CSS选择器权重
12. CSS选择器与DOM属性的优先级（#id 与 document[id="xx"]二者的优先级高低）
13. !important与行内样式的优先级

## JavaScript

### Basic

1. 闭包
2. 变量提升（变量声明和函数声明的区别）
3. 作用域
4. 事件（事件流）、事件捕获、事件冒泡
5. addEventListener与attachEvent的区别以及addEventListener各参数的含义
6. jQuery的事件机制及实现（on/bind/live/delegate的差异）
7. DOM相关操作（创建节点、删除节点）
8. 跨域（跨域的方式及实现）
9. 继承及原型链（继承的方式，原型链）
10. 正则表达式
11. call、apply、bind的区别
12. bind的实现及其返回值
13. ES 6箭头函数
14. ES 6的继承原理
15. ES 6 Generator

### React

1. V-DOM的优势
2. React的生命周期
3. setState的执行机制
4. 父子组件的通信

## Others

### HTTP

1. HTTP状态码
2. 301、302、304和307的区别
3. 304状态码是否还会发送请求？
3. cache-control有哪些值，分别表示什么含义？
4. url的query解析及RFC的相关定义：

	* 输入为：http://www.xxx.com/?a=1&b=ab，输出为：{a: 1, b: 'ab'}

	* 输入为：http://www.xxx.com/?a=1&b=ab&a=2，输出为：{a: [1, 2], b: 'ab'}

5. HTTP的method包含哪些？
6. POST请求与GET请求的差异
	
