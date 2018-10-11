# 行元素和块元素和行块元素
``` html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<body>
	<span>1</span>
	<span>2</span>
	<span>3</span>
	<div>1</div>
	<div>2</div>
	<div>3</div>
</body>
</html>
```
在浏览器中运行发现span元素是从左向右排列div元素是从上向下排列

行元素的特征是不能设置宽度和高度

块级元素可以设置margin,padding属性，行内元素的水平方向的padding-left和padding-right都会产生边距效果，但是竖直方向上的padding-top和padding-bottom都不会产生边距效果

行块是行元素的水平排列特征和块元素的可改变本身大小的特征 可以通过display:inline-block进行设置