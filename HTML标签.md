## HTML标签

> 超文本标记语言

通过一系列的标签来定义文本、图像、链接等等。HTML标签是由尖括号包围的关键字。

#### 基本格式

URL:

https://raw.githubusercontent.com/sanxiaojijiaben404/picture/main/QQ20251117-090721.png

#### 双标签，内容位于两个标签之间：

```
<p>这是一个段落. </p>

<h1>这是一个标题。 </h1>       有六种

<a href="#">这是一个超链接。</a>

<b>加粗</b>

<i>斜体</i>

<u>下划线</u>

<s>删除线</s>

<ul>
   <li>无序列表<li>
</ul>

<ol>
   <li>有序列表<li>
</ol>

<table border=1>         需要边框就加border
  <tr>
    <th>列标题1</th>
  </tr>
  <tr>
    <td>元素1</td>            biao
    <td>元素1</td>
  </tr>
</table>
```

#### 单标签（用于没有内容的元素）：

```
<input type="text">
<br>     换行标签
<hr>     分割线标签
```

很多其它的元素直接看菜鸟教程就行。

#### 属性：

> 用于定义元素的行为和外观，以及与其它元素的关系。                                                                                                
>
> <开始标签 属性名=“属性值”>

每个HTML元素可以具有不同的属性

1	<p id="describe" class="section">这是一个段落标签</p >

2	<a href=" ">这是一个超链接</a >  

属性名称不区分大小写，属性值对大小写敏感
1  < img src="example.jpg" alt="">

2   < img SRC="example.jpg" alt="">

3  < img src="EXAMPLE.JPG" alt="">

4	<!--前两者相同，第三个与前两个不一样-->

适用于大多数HTML元素的属性

class               为HTML元素定义一个或多个类名

id                       定义元素唯一的id

style                 规定元素的行内样式

> 练习：a标签的运用，img标签的运用

#### 块元素与行内元素

块元素（block）

> 块级元素通常用于组织和布局页面的主要结构和内容，例如段落、标题、列表、表格等。它们用于创建页面的主要部分，将内容分隔成逻辑块。

* 块级元素通常会从新行开始，并占据整行的宽度，因此它们会在页面上呈现为一块独立的内容块。
*  可以包含其他块级元素和行内元素。
* 常见的块级元素包括 <div>、<p>、<h1> 到 <h6>、<ul>、<ol>、<li>、<table>、<form> 等。

行内元素（inline）

> 行内元素通常用于添加文本样式或为文本中的一部分应用样式。它们可以在文本中插入小的元素，例如超链接、强调文本等。

* 行内元素通常在同一行内呈现，不会独占一行。
*  它们只占据其内容所需的宽度，而不是整行的宽度。
* 行内元素不能包含块级元素，但可以包含其他行内元素。
* 常见的行内元素包括 <span>、<a>、<strong>、<em>、<img>、<br>、<input> 等。

#### 表单

所有内容都要包含于<form>标签内

文本框的构建：

​           input标签中的text（框）、placeholder（虚写文字），value（实写文字），radio（选项），name（命名后可单选），password（密码），submit（上传）等属性

URL:

https://raw.githubusercontent.com/sanxiaojijiaben404/picture/main/Screenshot_20251117_152131.jpg

