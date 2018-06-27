#### JavaScript



#### CSS

##### 1.介绍一下 CSS 盒模型，什么时候会是 ie 的那种

css盒模型分为标准盒模型和ie盒模型

标准盒模型 宽高 ： 内容的宽高

ie盒模型 宽高 ： padding+border+宽高

IE8及其以上为w3c盒子模型 ,IE8以下的为IE 盒子模型 


##### 2.CSS 选择器优先级怎么计算

css和html三种关系

内嵌式：将css代码直接写在现有的html标签中，如<p style="color:red;font-size:12px">

嵌入式：把css样式代码写在<style type="text/css"></style>标签之间

外部式：把css代码写一个单独的外部文件中，这个css样式文件以“.css”为扩展名，在<head>内（不是在                 

                  <style>标签内使用<link>标签将css样式文件链接到HTML文件内，如下面代码：

                           <link href="base.css" rel="stylesheet" type="text/css" />

  优先级    内联式 > 嵌入式 > 外部式

计算

第一等：代表内联样式，如: style="xxx"，权值为1000。

第二等：代表ID选择器，如：#content，权值为100。

第三等：代表类，伪类和属性选择器，如.content，:hover，[attribute]，权值为10。

第四等：代表元素选择器和伪元素选择器，如div，p，权值为1。



##### 3.position 的值，应用场景。

absolute:生成绝对定位的元素，相对于 static 定位以外的第一个父元素进行定位。元素的位置通过 "left", "top", "right" 以及 "bottom" 属性进行规定。

static:默认值。没有定位，元素出现在正常的流中（忽略 top, bottom, left, right 或者 z-index 声明）。 

relative: 生成相对定位的元素，相对于其正常位置进行定位。因此，"left:20" 会向元素的 LEFT 位置添加 20 像素。 

fixed:生成绝对定位的元素，相对于浏览器窗口进行定位。元素的位置通过 "left", "top", "right" 以及 "bottom" 属性进行规定。



#### 数据结构





#### HTTP

##### 1.TCP 三次握手



 

 

 

 

 










