# JavaScript

### 1.变量声明：

* let （块级作用域，可修改）
*  const （块级作用域，不可修改，必须初始化）
*  var （函数级作用域，尽量少用）

### 2.数据类型：

* 基本类型

 String （字符串）、 Number （数字）、Undefined （未定义）、 Null （空值）、 Symbol （唯一标识）

* 引用类型

  Function （函数）

* 运算符

  算术（ +、-、*、/ ）

  比较（ == 值相等， === 值和类型都相等）

  逻辑（ && 与、 || 或、 ! 非

### 3.控制语句

#####     条件语句

​    if  else 

#####     循环语句

​    for循环

​    while循环

> 这部分跟c语言一模一样

### 4.函数

* 声明式： function 函数名(参数){ 代码 } 
* 箭头函数： (参数) => { 代码 } 

### 5.数组方法：

* 遍历： forEach((item, index) => {}) 

- 筛选： filter(item => 条件) （返回新数组）
- 映射： map(item => 处理逻辑) （返回新数组，修改每个元素）

### 6.JS事件

> 事件是文档或浏览器窗口中发生的特定瞬间，例如用户的点击、键盘的按下、页面的加载等。
>
> 下面是一些常见的事件

| 事件        | 描述             |
| ----------- | ---------------- |
| onClick     | 点击事件         |
| onMouseOver | 鼠标经过         |
| onMouseOut  | 鼠标移出         |
| onChange    | 文本内容改变事件 |
| onSelect    | 文本框选中       |
| onFocus     | 光标聚集         |
| onBlur      | 光标离开         |

### 7.DOM操作

1. 选择元素：
-  document.getElementById("id") （通过ID选）
-  document.querySelector("选择器") （选第一个匹配元素）。

2. 修改内容/样式：
- 内容： 元素.innerText = "新内容" 
- 样式： 元素.style.样式名 = "值" （如 element.style.color = "red" ）。
3. 事件绑定： 元素.addEventListener("事件名", 回调函数) （如 click 点击事件）。

### 参考

[]3小时前端入门教程（HTML+CSS+JS）([3小时前端入门教程（HTML+CSS+JS）_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1BT4y1W7Aw/?spm_id_from=333.1007.0.0&vd_source=2e665bb499620ff7c35d9d551c1ca19e))

[菜鸟教程]（[菜鸟教程 - 学的不仅是技术，更是梦想！](https://www.runoob.com/)）

[DeepSeek]（[DeepSeek | 深度求索](https://www.deepseek.com/)）

谷歌浏览器