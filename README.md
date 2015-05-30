#前端基础#
##网页布局基础##
CSS的定位机制有3种：

1. 标准文档流（Normal flow，从上到下，从左到右就像写文章一样，由块级元素和行级元素组成）。
2. 浮动（float）。
3. 绝对定位（absolute）。

----------

- 块级元素：从左到右撑满页面，独占一行，当碰到页面边缘的时候自动换行，如div、ul、li、p、dl、dt等。
- 行级元素：能在同一行显示，不会改变html文档的结构，如：span、img、strong、input等大部分的表单标签。
- 行级元素和块级元素都是盒子模型。

### 盒子模型 ###
![](http://i.imgur.com/xJV03Ss.jpg)
盒子模型其实是3D立体模型。
![](http://i.imgur.com/fWpDo8i.jpg)
各个层次之间相互叠加就形成了平面模型。

网页的布局其实就是利用CSS处理块与块之间的关系：

1. 块挨着块；
2. 块嵌套者块；
2. 块叠加这块。


----------

- 单列布局
例如百度。简单、主题突出、不适合防止多行文本。
- 双列布局
- 三列布局

#注意事项#
1 .CSS中只有多行注释，在其他语言中的"//"方式是不行的。