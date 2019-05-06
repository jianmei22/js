# js
JS代码原则：高内聚，弱耦合
1. ecmascript是一种语言标准，第一版标准发布于1997年，javascript是网景公司对ecmascript标准的一种实现。
2. js不区分整数和浮点数，统一用number表示，nan表示 not a number,无法计算结果的时候用nan表示。
3. 字符串string,是以单引号或者双引号括起来的任意文本，比如'abc',"abc".
4. 布尔值boolean,布尔值只有两种值，true或者false。
5. &&与，||或，！非。 
6. 编程形式的区别：面向对象、面向过程
7. typeof:六种数据类型：number string boolean undefined object function
typeof返回的是对象的两个object：null和{}
3.8
1. 浏览器组成
 	shell部分
 	内核部分
	渲染引擎（html和css基础语法识别、语法规则和渲染）
	js引擎
	其他模块
2008年谷歌发布最新浏览器chrome，能把js代码直接转化成机械码来执行。
2. js特点
js是解释性语言（浏览器读一行翻译一行，php/python也是解释性语言）
优点：跨平台、单线程（异步传输数据：）
不足：速度较慢
3. js标准
标准是由ecma制定的 所以有时候也叫ecmascript
延申两个部分dom bom
js三大部分：ecmascript、dom、bom
js执行队列：单线程，解释性语言，异步传输
4. 主流浏览器的内核及私有前缀  

ie     内核：trident   私有前缀：-ms-  

chrome       webkit/blink    -webkit-  

firefox      gecko       -moz- 

opera        presto        -o- 

safari       webkit   -webkit-

# jQuery
