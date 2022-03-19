# jQuery的设计思想

## 1. jQuery 如何获取元素
* ```jQuery('div')``` 或简写```$('div')``` （以下都按简写）  获取所有div元素
* ```$('#xxx')``` 获取id为xxx的元素
* ```$('div.red')``` 获取class名为red 的div 元素
## 2.jQuery 的链式操作是怎样的
* 因为jQuery每次返回的都是一个对象，所以能够链式操作
* ```$('div').has('a').end().has('p')```  获取div中的a标签 再退出，再获取div里面的p标签
## 3.jQuery 如何创建元素
* 直接把要创建的元素传入即可
* ```$('<p>hello</p>')```
* ```$('div').append('<a href="github.com"></a>')```在div元素里面添加a标签
## 4.jQuery 如何移动元素
* ```$('div').insertAfter($('p'))``` 把div移动到p后面 //返回的是div
* ```$('div').after($('p'))```  把div加到p前面 //返回的是p
```　
.appendTo()和.append()：//在现存元素的内部，从后面插入元素
.prependTo()和.prepend()：//在现存元素的内部，从前面插入元素
```
## 5.jQuery 如何修改元素的属性
``` 
　　.html() 取出或设置html内容
　　.text() 取出或设置text内容
　　.attr() 取出或设置某个属性的值
　　.width() 取出或设置某个元素的宽度
　　.height() 取出或设置某个元素的高度
　　.val() 取出某个表单元素的值
```
