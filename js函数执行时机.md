# js函数执行时机
* ```let i ```    定义了i为全局变量
* 然后进行for循环 ，在每一次的for循环中 创建了一个setTimeout 定时器，该定时器还没执行里面的函数，先通过所有的for循环，结束一共创建了6个定时器，此时i=6，然后执行定时器里面的打印内容，所以打出了6个6

```
for(let i=0;i<6;i++){
    setTimeout(()=>{
    console.log(i);
    },0)
 }
```
* 把i定义成局部变量 这样每一次的for循环都会创建一个独立的i的定时器 

```
let i = 0
for (i = 0; i<6; i++){    
    setTimeout((i) =>{
        console.log(i)
    },0,i)
}
```
