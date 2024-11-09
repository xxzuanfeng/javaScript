# Learn the Date Object

```js
const currentDate = new Date();						//创建日期对象
const day = date.getDate();							//获取当前日期，1-31
const month = date.getMonth() + 1;					//.getMonth()方法获取当前月份，0-11
const year = date.getFullYear();					//.getFullYear()获取当前年份
const hours = date.getHours();						//.getHours()获取小时数，0-23,0为子夜，23为11pm
const minutes = date.getMinutes();					//.getMinutes()获取分钟数，0-59
"hello".split(""); 								//.split()方法以某个字符为分隔符分割字符串然后返回数组

element.addEventListener("change", () => {});		//检测HTML的value值变化
//switch 语句
switch (dayOfWeek) {
  case 1:
    console.log("It's Monday!");
    break;
  case 2:
    console.log("It's Tuesday!");
    break;
  // ...cases for other workdays
  default:
    console.log("It's the weekend!");
}
[1, 2, 3, 4, 5].reverse();						//.reverse()方法翻转元素顺序

// returns "1-2-3-4-5"
[1, 2, 3, 4, 5].join("-");

break;										//中断选择
```

