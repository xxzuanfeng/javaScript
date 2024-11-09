# Learn Form Validation

```js
document.getElementById('title');				//获取html中id为title元素
const regex = /hello/;							//正则表达式用两个斜线包括表示
/\+=\s/										 //\s匹配空白字符
/[+=\s]/									//[char]字符类，匹配括号类任一字符，即+ - 空格
/[+-\s]/g									//末尾/后加g更改模式匹配行为，g代表global，全局匹配。
str.replace(/[+-\s]/g, "")					//replace方法用于更换匹配的字符。
/Hello/i									//i匹配模式表示大小写不敏感，insensitive
[0-9]										//匹配任意数字
[0-9]+										//匹配任一数字一次或多次
\d											//匹配任意数字，\d跟[0-9]一样。
str.match(regex);							//.match方法返回匹配的数列。
`Hello, my name is ${name}~!`				//``允许在字符串中插入变量，${}中插入。
targetInputContainer.querySelectorAll()		//返回类似数组的对象。
formElement.innerHTML += formContent;		//网页中增加内容
addEntryButton.addEventListener("click", addEntry);		//.addEventListener方法监控点击事件，触发函数
55
```

