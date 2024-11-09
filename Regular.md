# Learn Regular Expressions

```js
const helpRegex = /please help/;					//匹配please help字符
const helpRegex = /please help/i;					//i模式忽略大小写
msg.match(helpRegex);								//.match()方法接受正则作为参数决定字符串是否匹配表达式
heplRegex.test(msg);								//.text()方法测试字符串是否匹配表达式，返回布尔类型
const helpRegex = /please help|assist me/i;			// | 符号即匹配左边又匹配右边
arr.some(() => {});								//数组中至少有一个元素满足回调函数，.some()方法就返回true	
const dollarRegex = /[0-9] dollars/i;				//[] 代表字符类，[0-9]匹配0到9这9个数字
const dollarRegex = /[0-9]+ dollars/i;              // +代表匹配一次或多次
/h(i|ey) camper/;								//捕获组，可以匹配hi camper 或者 hey camper 提取共同部分
/colou?r/										//匹配0次或多次 color   colour  u可选
\s+;												//匹配0次或多次空格
(?:a|b);										//?:即匹配a也匹配b但不保存结果,转换成非捕获组
\s											//匹配spaces,tabs,line breaks
^											//匹配字符串开始
$											//匹配字符换结尾
```

