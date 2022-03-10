# JS对象总结
### 声明对象的两种语法
 ```
 let obj = {} 
 let obj = new Object();
 ```
 ### 如何删除对象的属性
 ```
 delete obj.属性名  
 delete obj['属性名']  
 obj.属性名=undefined
 ```
 ### 如何查看对象的属性
 ```
 Object.keys(obj) --看属性名
 Object.values(obj) --- 看属性值
 console.dir(obj)   --- 看名和值
 ```
 ### 如何修改或增加对象的属性
 ```
 obj.属性名=   --直接修改 或增加
 Obejct.assig(obj,{name:fxj,age:20,sex:man;})---批量增加
 Object.creat()  增加的是原型   
 ```
 ### 'name' in obj和obj.hasOwnProperty('name') 的区别
  *  hasOwnProperty  找不到原型链上的属性   例如 obj.hasOwnProperty('hasOwnProperty')  返回的是false
  
