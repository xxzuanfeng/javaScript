# Learn Basic String and Array Methods

```js
new Audio();						//创建一个audio元素
[...Arr1, ...Arr2]					//spread 复制所有元素从一个数组到另一个数组

// 箭头函数用法
const exampleFunction = () => {
  // code goes here
}
const multiplyTwoNumbers = (num1, num2) => num1 * num2;			//单行时忽略花括号和return
const doubledNumbers = numbers.map((number) => number * 2); 	// doubledNumbers will be [2, 4, 6]，遍历数组，从一个数组得到另一个数组。

//.join方法把数组转换成一个字符串
const exampleArr = ["This", "is", "a", "sentence"];
const sentence = exampleArr.join(" "); // Separator takes a space character
console.log(sentence); // Output: "This is a sentence"
userData?.songs										//访问不存在的属性时不会抛出错误
array.sort();									//.sort方法把数组元素转换成字符串然后按照'utf-16'编码排序

//find方法检索第一满足条件的元素
const numbers = [10, 20, 30, 40, 50];
// Find the first number greater than 25
const foundNumber = numbers.find((number) => number > 25);
console.log(foundNumber); // Output: 30

audio.play();									//.play()方法播放mp3文件
audio.pause();									//.pause()方法暂停播放

const animals = ["dog", "cat", "horse"];
animals.indexOf("cat") // 1						//.indexOf()返回列表元素索引

//forEach遍历数组中每个元素
const numbers = [1, 2, 3, 4, 5];
// Using forEach to iterate through the array
numbers.forEach((number) => {
  console.log(number); // 1, 2, 3, 4, 5
});

songEl.removeAttribute("aria-current")				//removeAttribute()方法移除元素某个属性
element.textContent；							//textContent为元素标签内容
names.sort(() => Math.random() - 0.5);				//数组的随机排序
array.filter(() => {});								//filter方法只保留满足回调函数的元素
document.createElement(tagName)						//在HTML中创建标签
document.createTextNode("your text")				//创建文本
parentElement.appendChild(parentElementText)		//添加子元素
```

