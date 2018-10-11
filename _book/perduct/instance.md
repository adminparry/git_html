# 每个元素都是一个实例
实际上浏览器是对html进行解析的其解析过程就是标签映射的对象进行了实例
这个特征我们可以通过JavaScript的方式得到了解

``` javascript
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<body>
	<div id="box"></div>
</body>
<script>
	var instance = document.getElementById('box').constructor
	<!-- ƒ HTMLDivElement() { [native code] } -->
</script>
</html>
```

# 每个元素都有自己的特性
例如img可以拉取图片资源
input可对键盘输入
div可以设置align
所以html的标签才会被设计出很多