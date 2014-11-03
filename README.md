jQuery-learning
===============

Learn about jQuery 

JQUERY语法
语法 $(selector).action()
$定义jquery selector 查找html元素  action 元素操作

元素选择器

$(this).hide() - 隐藏当前元素

$("p").hide() - 隐藏所有段落

$(".t").hide() - 隐藏所有 class="t" 的所有元素

$("p.t").hide()    隐藏所有class=“t”的<p>元素

$("#t").hide() - 隐藏所有 id="t" 的元素

$("p#t").hide()-隐藏所有id=“t”的<p>元素


属性选择器

jQuery 使用 XPath 表达式来选择带有给定属性的元素。

$("[href]") 选取所有带有 href 属性的元素。

$("[href='#']") 选取所有带有 href 值等于 "#" 的元素。

$("[href!='#']") 选取所有带有 href 值不等于 "#" 的元素。

$("[href$='.jpg']") 选取所有 href 值以 ".jpg" 结尾的元素。


CSS 选择器

jQuery CSS 选择器可用于改变 HTML 元素的 CSS 属性。
下面的例子把所有 p 元素的背景颜色更改为红色：
$("p").css("background-color","red");
