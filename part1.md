markdown 语法说明
=============

* 兼容HTML
eg: 插入html表格
<table>
  <tr>
    <td>line1</td>
    <td>row1</td>
  </tr>
  <tr>
    <td>line2</td>
    <td>row2</td>
  </tr>
</table>

在 HTML 区块标签间的 Markdown 格式语法将不会被处理。比如，你在 HTML 区块内使用 Markdown 样式的*强调*会没有效果

* & 和 < 

这是一个版权符号 
&copy; all rights reserved

但是下面这个&就会自动转化为`AT&amp;T`

AT&T

4 < 5

markdown 会自动转化为`4 &lt; 5`

区块和段落
==============

总共有两种表示标题的方法 setext和atx

* setext

利用`=` 和 `-` 表示第一级分类和第二级分类，任何数量的`=`和`-` 都有同样的效果
是在文字说明后面使用`=`和`-`


第一级
=================
第二级
--------------

* atx

在行首插入1~6个`#`,1最大，6最小，为了美观，可以在行尾也加上相应的#,行尾的数量也不用和行首的一样,因为只有行首的起控制作用

# H1 #
## H2 ##
### H3 ###
#### H4 ####
##### H5
######H6

* 区块引用Blockquotes

每行前面加上`>`
> 1. 111
> 2. 222
> 3. 333

> 1. 444
2. 555
3. 666

嵌套里可以放嵌套
> 1.777
>>  1.1. 888
>>  1.2. 999
> 2. 000


> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

嵌套里可以放其他MD元素
> ## title
>
> 1. line1
> 2. line2
>
> type some thing
>
> Go Rockets







