# 重排

重排也叫回流

当页面布局和几何属性改变时就需要回流。下述情况会发生浏览器回流：

1、添加或者删除可见的DOM元素；

2、元素位置改变；

3、元素尺寸改变——边距、填充、边框、宽度和高度

4、内容改变——比如文本改变或者图片大小改变而引起的计算值宽度和高度改变；

5、页面渲染初始化；

6、浏览器窗口尺寸改变——resize事件发生时；