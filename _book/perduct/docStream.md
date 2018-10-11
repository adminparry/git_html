# 文档流的概念
书写html的时候视乎也可以看做成写文档或者写文章那么文档流就是文章的排列要么是横着排要么是竖着排所以就有行元素和块元素那么如果我们让本身的行元素或者块元素改变特征那么我们就称为是脱离文档流通常为浮动和绝对定位
float和position:absolute

``` html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<body>
	<div style="float:left">1</div>
	<div style="float:left">2</div>
	<div style="float:left">3</div>
	<span style="position:absolute">1</span>
	<span style="position:absolute">2</span>
	<span style="position:absolute">3</span>
</body>
</html>
```