# Learn Fetch and Promises    Asynchronous

```js
//网址发送get请求，.then()访问响应。.json()方法返回响应类的JSON方法。
fetch("url-goes-here")
	.then(res => res.json())
	.catch(err => console.error(`There was an error: ${err}`))						
arr.slice(startingIndex, endingIndex);

const example = async () => {
    const data = await fetch("https://example.com/api")
    console.log("this is an example");
}

try {
    const name = "freeCodeCamp";
    name = "fCC";
}	catch (err) {
    console.log(err);
}
```

