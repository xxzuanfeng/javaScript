# Learn Introductory JavaScript

```javascript
let hello;						//声明变量，可包含字符、数字、dollar符号、下划线，不能包含空格，不能数字开头。
let character = "hello"			//变量赋值初始化
console.log(character);			//打印变量
character = "World";			//重新分配变量的值，不加let，
let secondCharacter;			//驼峰命名法，首个单词小写，后面的单词首字母大写
let count = 8;					//声明数值变量时，不用引号
console.log(count + 1);			//执行数学运算
let array = [];					//声明数列，可以包含多中数据类型
let rows = ["Naomi", "Quincy", "CamperChan"];		//数值之间逗号隔开
console.log(rows[0]);								//访问数组第一个值
rows[2] = 10;										//数值可随意更改；
array.length										//返回数组长度；
rows.push("freeCodeCamp");							//在数组末尾添加值，返回数组新的长度
let popped = rows.pop();							//pop方法移除数组中最后一个值并返回。
const												//声明常量，不能更改，不能不初始化。
//for 循环
for (iterator; condition; iteration) {
  logic;
}
//i = i + 1    i++  i +=1
for (let i = 0; i < count; i = i + 1) {
  console.log(i);
}
//for ... of 循环
for (const value of iterable) {

}

string.repeat(3);									//字符串重复三次
//函数
function name(parameter) {

}
name();								//调用函数
//变量氛围全局变量和局部变量

/*
*/  //多行注释

//if语句
if (condition) {
  logic
}

//false, 0, "", null, undefined, NaN   为假

if (condition1) {
  // code to run if condition1 is true
} else if (condition2) {
  // code to run if condition2 is true
} else if (condition3) {
  // code to run if condition3 is true
} else {
  // this code will run 
  // if the first and second conditions are false
}
//while 循环
while (condition) {
  logic;
}

==							//判断两个值相当 "0" == 0 为真
===							//判断两个值数值和类型都相同
!==							//判断两只值不相等
    
array.unshift(3);			//在数组的开头位置添加元素
array.shift();				//去除数组第一个元素，然后返回剩余的
```

