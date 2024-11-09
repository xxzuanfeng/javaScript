# Learn Recursion

```js
numberInput.addEventListener("keydown",() => {});  //keydown 按下键盘上某个键触发

//parseInt()方法把字符串转换成整数					
parseInt(2.2); // 2	
parseInt("2e+3"); // 2
parseInt("e") // NaN

//isNaN()如果是NaN则返回true
isNaN("test"); // true
isNaN(2); // false
isNaN("3.5"); // false

String();					//将数据转换成字符串
//setTimeout()第一个参数为回调函数，第二个参数为时间毫秒代表多久后执行  异步执行
setTimeout(() => {
  console.log("Hello, world!");
}, 3000);
```

