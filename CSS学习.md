# CSS学习

> 描述HTML元素的显示方式，控制网页的布局、颜色、字体等外观，实现内容与表现的分离
>
> 用vscode编很方便

### CSS 三种导入方式

1. 内联样式（Inline Styles）

   ```
   <p style="color: red;">文字</p>
   ```

2. 内部样式表（Internal Stylesheet）

   ```
   <style> p { color: red; } </style>
   ```

3. 外部样式表（External Stylesheet）

   ```
    <link rel="stylesheet" href="style.css">
   ```

   * 三种导入方式的优先级：内联样式 > 内部样式表 > 外部样式表

### 基本语法

选择器{

​     属性：值；

​     属性：值；

}

### 选择器

> 选择器是 CSS 中的关键部分，它允许你针对特定元素或一组元素定义样式

| 元素选择器   | P       | 选择所有<p>标签                  |
| ------------ | ------- | -------------------------------- |
| 后代选择器   | div p   | 选择 <div> 内部所有的 <p>        |
| 子元素选择器 | div > p | 选择 <div> 直接子元素的 <p>      |
| 相邻兄弟     | h1 + p  | 选择紧接在 <h1> 之后的第一个 <p> |
| 通用兄弟     | h1 ~ p  | 选择 <h1> 之后所有的兄弟 <p>     |
| 类选择器     | .intro  | 选择 class="intro" 的元素        |
| ID选择器     | #header | 选择 id="header" 的元素          |
| 通用选择器   | *       | 选择所有元素                     |

还有 伪选择器

 ### 属性

各类属性在菜鸟教程里面十分详尽，直接看菜鸟。

e.g:[attribute] [target] 选择带有 target 属性的元素
[attr=value] [target="_blank"] 选择 target="_blank" 的元素
[attr^=value] [class^="top"] 选择 class 以 "top" 开头 的元素
[attr$=value] [src$=".pdf"] 选择 src 以 ".pdf" 结尾 的元素
[attr*=value] [class*="test"] 选择 class 中包含 "test" 的元素

### 伪类和伪元素

伪类：定义元素的特殊状态。

伪元素：定义元素的特定部分。（目前只知道伪元素前面用::）

### 盒模型

>  所有HTML元素都可以看作一个盒子

包括：内容：width, height
内边距：padding（内容与边框的距离）
边框：border
外边距：margin（盒子与其他盒子的距离）

### 布局

网页布局：

* 标准流
* 浮动
* 定位
* Flexbox（一维布局）和Gril（二维布局）

注：px    （是 像素）

### 参考

[]3小时前端入门教程（HTML+CSS+JS）([3小时前端入门教程（HTML+CSS+JS）_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1BT4y1W7Aw/?spm_id_from=333.1007.0.0&vd_source=2e665bb499620ff7c35d9d551c1ca19e))

[菜鸟教程]（[菜鸟教程 - 学的不仅是技术，更是梦想！](https://www.runoob.com/)）

[DeepSeek]（[DeepSeek | 深度求索](https://www.deepseek.com/)）

谷歌浏览器

百度浏览器