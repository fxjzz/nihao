# CSS知识总结

## 浏览器的渲染原理

   浏览器会得到html  再请求加载css组件  根据css的不同属性分别渲染元素   然后在进行布局 绘制 和 合成  做成层叠关系...

## CSS 动画的两种做法（transition 和 animation）
   1、transition 用于变形、过渡 。在父元素中添加transition: transform 1s;  1s表示变换到另一个的时间
   
transfrom给子元素 , 比如给子元素一个transform : translateX(100px); 则会让该子元素向这 X轴移动100px;
   
   2、animation  需要加@keyframes 变量名{0%{添加改变的量}50%{改变的量}100%{改变的量}}
   
   再在父元素中添加animation : 变量名  +  变化的时间  +等等;
   
## 其他

position 定位   子绝父相   子元素用绝对定位  父元素必须要用相对定位

用定位后要给子元素添加 top left 等，z-index表示层级，opacity：表示整个元素的透明度

justify-content 是x轴的位置   align-content y轴

flex-direction flex-wrap 
   
   



