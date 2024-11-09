# Learn Basic JavaScript

```html
<!--添加script脚本-->
<script>
  // JavaScript code goes here
</script>
<script src="./script.js"></script>				<!--链接到JS文件-->

```

```javascript
document.querySelector("h1");				//documnent代表整个HTML文档，querySelector接受CSS选择器的参数，返回匹配的第一个元素
button.onclick = myFunction;				//button元素的onclick属性可以决定点击按钮时的行为。
info.innerText = "Hello World"; 			//innerText属性可以改变元素的文本内容
//对象数据类型，键值对形式。
{
  key: value
}
//键中有空格时，用双引号引起来
const spaceObj = {
  "Space Name": "Kirk",
};

//当知道属性时可以用点访问属性
const developer = {
  name: "Jessica",
}
// Output: Jessica
console.log(developer.name); 
//当键中包含空格时，用[]访问属性
const spaceObj = {
  "Space Name": "Kirk",
};

spaceObj["Space Name"]; // "Kirk"

paragraph.style.display = 'block';					//更改样式的display属性
Math.random();										//产生一个0到1的随机数，包含0不包含1
Math.floor();										//向下取整
text.innerHTML										//用于JS修改HTML内容
```

```css
display: none;							/*隐藏元素*/
cursor: pointer;						/*游标改变样式，变成手形状*/
59

```

