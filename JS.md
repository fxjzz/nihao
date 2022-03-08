# JavaScript 的历史 

*JavaScript最初由Netscape的Brendan Eich设计，最初将其脚本语言命名为LiveScript，后来Netscape在与Sun合作之后将其改名为JavaScript。JavaScript最初受Java启发而开始设计的，目的之一就是“看上去像Java”，因此语法上有类似之处，一些名称和命名规范也借自Java，但JavaScript的主要设计原则源自Self和Scheme。JavaScript与Java名称上的近似，是当时Netscape为了营销考虑与Sun微系统达成协议的结果。微软同时期也推出了JScript来迎战JavaScript的脚本语言。
发展初期，JavaScript的标准并未确定，同期有Netscape的JavaScript，微软的JScript和CEnvi的ScriptEase三足鼎立。为了互用性，Ecma国际（前身为欧洲计算机制造商协会）创建了ECMA-262标准（ECMAScript），两者都属于ECMAScript的实现，尽管JavaScript作为给非程序人员的脚本语言，而非作为给程序人员的脚本语言来推广和宣传，但是JavaScript具有非常丰富的特性。 [10]  1997年，在ECMA（欧洲计算机制造商协会）的协调下，由Netscape、Sun、微软、Borland组成的工作组确定统一标准：ECMA-262。完整的JavaScript实现包含三个部分：ECMAScript，文档对象模型，浏览器对象模型。 [9] 
JavaScript是甲骨文公司的注册商标。Ecma国际以JavaScript为基础制定了ECMAScript标准。JavaScript也可以用于其他场合，如服务器端编程（Node.js）。

# JavaScript 诞生记

* 1995年5月，网景公司做出决策，未来的网页脚本语言必须"看上去与Java足够相似"，但是比Java简单，使得非专业的网页作者也能很快上手。这个决策实际上将Perl、Python、Tcl、Scheme等非面向对象编程的语言都排除在外了。

Brendan Eich被指定为这种"简化版Java语言"的设计师。


* 但是，他对Java一点兴趣也没有。为了应付公司安排的任务，他只用10天时间就把Javascript设计出来了。

* 由于设计时间太短，语言的一些细节考虑得不够严谨，导致后来很长一段时间，Javascript写出来的程序混乱不堪。

# JavaScript 的10个设计缺陷

* 不适合开发大程序

* Javascript提供的标准函数库非常小，只能完成一些基本操作，很多功能都不具备。
* null属于对象（object）的一种，意思是该对象为空；undefined则是一种数据类型，表示未定义。
* 全局变量难以控制
* 自动插入行尾分号
* 加号运算符  "123"+"456"
* NaN是一种数字，表示超出了解释器的极限。
*  ==和===    ==用来判断两个值是否相等。当两个值类型不同时，会发生自动转换，得到的结果非常不符合直觉。
* Javascript的数组也属于对象（object），所以要区分一个对象到底是不是数组，相当麻烦。
* Javascript有三种基本数据类型：字符串、数字和布尔值。它们都有相应的建构函数，可以生成字符串对象、数字对象和布尔值对象。
