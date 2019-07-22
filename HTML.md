# HTML

标签（空格分隔）： w3school教程

---
### HTML简介
- HTML 是用来描述网页的一种语言。
>HTML 指的是超文本标记语言 (Hyper Text Markup Language)
HTML 指的是超文本标记语言 (Hyper Text Markup Language)

- HTML标签 (HTML tag)
>HTML 标签是由尖括号包围的关键词，比如 &lt;html>
HTML 标签通常是成对出现的，比如 &lt;b&gt; 和 &lt;/b&gt;
标签对中的第一个标签是开始标签，第二个标签是结束标签
开始和结束标签也被称为开放标签和闭合标签

- HTML文档=网页
>HTML 文档包含 HTML 标签和纯文本
HTML 文档描述网页 也被称为网页

**HTML编译器**： 用记事本（mac用textedit）
打开记事本写html代码-->保存为html格式，后缀为.htm或.html-->打开这个保存为html格式的文档，即打开其网页

### HTML标签
html标题：用&lt;h1&gt;-&lt;h6&gt;等标签来定义
```
<h1>This is a heading</h1>
<h2>This is a heading</h2>
<h3>This is a heading</h3>
```
html段落：用&lt;p&gt;标签来定义
html链接：用&lt;a&gt;标签来定义;注：在 href 属性中指定链接的地址。
```
 <a href="http://www.w3school.com.cn">This is a link to w3school</a>
```
 <a href="http://www.w3school.com.cn">This is a link to w3school</a>
html图片：用&lt;img&gt;标签来定义；注：图像的名称和尺寸是以属性的形式提供的，所以我们加“”
```
<img src="w3school.jpg" width="104" height="142" />
```

### HTML元素
>HTML 元素指的是从开始标签（start tag）到结束标签（end tag）的所有代码。大多数 HTML 元素可拥有属性
大多数 HTML 元素可以嵌套（可以包含其他 HTML 元素）。

1. HTML 文档由嵌套的 HTML 元素构成。


**HTML 文档实例**

<pre>
&lt;html&gt;

&lt;body&gt;
&lt;p&gt;This is my first paragraph.&lt;/p&gt;
&lt;/body&gt;

&lt;/html&gt;
</pre>

<p>上面的例子包含三个 HTML 元素: &lt;p&gt;元素,&lt;body&gt;元素，&lt;html&gt;元素</p>


<pre>&lt;p&gt;This is my first paragraph.&lt;/p&gt;</pre>
<pre>
&lt;body&gt;
&lt;p&gt;This is my first paragraph.&lt;/p&gt;
&lt;/body&gt;
</pre>

<pre>
&lt;html&gt;

&lt;body&gt;
&lt;p&gt;This is my first paragraph.&lt;/p&gt;
&lt;/body&gt;

&lt;/html&gt;
</pre>

2.空的HTML元素：
&lt;br/&gt;换行
### HTML属性 和 HTML样式（样式要学了CSS后再看）
待补充

### HTML常见标签
&lt;html&gt; :&emsp;定义HTML文档，&lt;html&gt; 与 &lt;/html&gt; 之间的文本描述网页
&lt;body&gt; :&emsp;定义文档主体，&lt;body&gt; 与 &lt;/body&gt; 之间的文本是可见的页面内容
&lt;br/&gt;:  &emsp;&emsp;换行
&lt;hr/&gt;: &emsp;&emsp;水平线
&lt;!-- --&gt;:&ensp; HTML注释

**示例**（水平线，注释）
<pre>
&lt;p&gt;This is a paragraph&lt;/p&gt;
&lt;hr /&gt;
&lt;p&gt;This is a paragraph&lt;/p&gt;
&lt;hr /&gt;
&lt;p&gt;This is a paragraph&lt;/p&gt;
</pre>

<pre>
&lt;!-- This is a comment --&gt;
</pre>
<br/>
### HTML文本格式化
>1.文本格式化
2.预格式文本
3.“计算机输出”标签
4.引用、引用和术语定义
5.地址
6.缩写和首字母缩写
7.文字方向
8.删除字效果和插入字效果








<h4 style="text-align:center">1.文本格式化标签</h4>

<table class="dataintable">
<tr>
<th style="width:30%">标签</th>
<th style="width:70%">描述</th>
</tr>
<tr>
<td><a href="/tags/tag_font_style.asp">&lt;b&gt;</a></td>
<td>定义粗体文本。</td>
</tr>
<tr>
<td><a href="/tags/tag_font_style.asp">&lt;big&gt;</a></td>
<td>定义大号字。</td>
</tr>
<tr>
<td><a href="/tags/tag_phrase_elements.asp">&lt;em&gt;</a></td>
<td>定义着重文字。</td>
</tr>
<tr>
<td><a href="/tags/tag_font_style.asp">&lt;i&gt;</a></td>
<td>定义斜体字。</td>
</tr>
<tr>
<td><a href="/tags/tag_font_style.asp">&lt;small&gt;</a></td>
<td>定义小号字。</td>
</tr>
<tr>
<td><a href="/tags/tag_phrase_elements.asp">&lt;strong&gt;</a></td>
<td>定义加重语气。</td>
</tr>
<tr>
<td><a href="/tags/tag_sup.asp">&lt;sub&gt;</a></td>
<td>定义下标字。</td>
</tr>
<tr>
<td><a href="/tags/tag_sup.asp">&lt;sup&gt;</a></td>
<td>定义上标字。</td>
</tr>
<tr>
<td><a href="/tags/tag_ins.asp">&lt;ins&gt;</a></td>
<td>定义插入字。</td>
</tr>
<tr>
<td><a href="/tags/tag_del.asp">&lt;del&gt;</a></td>
<td>定义删除字。</td>
</tr>
<tr>
<td><a href="/tags/tag_strike.asp">&lt;s&gt;</a></td>
<td class="deprecated"><em>不赞成使用。</em>使用 &lt;del&gt; 代替。</td>
</tr>
<tr>
<td><a href="/tags/tag_strike.asp">&lt;strike&gt;</a></td>
<td class="deprecated"><em>不赞成使用。</em>使用 &lt;del&gt; 代替。</td>
</tr>
<tr>
<td><a href="/tags/tag_u.asp">&lt;u&gt;</a></td>
<td class="deprecated"><em>不赞成使用。</em>使用样式（style）代替。</td>
</tr>
</table>

<br/>
<h4 style="text-align:center">2.预格式文本</h4>
<p>用&lt;pre&gt;标签，下面示例 和 效果网页图片</p>
![image_1dftv9b8justl2t5j616oao3l9.png-54.1kB][1]
<br/>
<h4 style="text-align:center">3.“计算机输出”标签</h4>
<table class="dataintable">
<tr>
<th style="width:30%">标签</th>
<th style="width:70%">描述</th>
</tr>
<tr>
<td><a href="/tags/tag_phrase_elements.asp">&lt;code&gt;</a></td>
<td>定义计算机代码，即编程代码示例</td>
</tr>
<tr>
<td><a href="/tags/tag_phrase_elements.asp">&lt;kbd&gt;</a></td>
<td>定义键盘码（键盘输入）。</td>
</tr>
<tr>
<td><a href="/tags/tag_phrase_elements.asp">&lt;samp&gt;</a></td>
<td>定义计算机代码样本（也定义计算机输出示例）。</td>
</tr>
<tr>
<td><a href="/tags/tag_font_style.asp">&lt;tt&gt;</a></td>
<td>定义打字机代码。</td>
</tr>
<tr>
<td><a href="/tags/tag_phrase_elements.asp">&lt;var&gt;</a></td>
<td>定义变量。</td>
</tr>
<tr>
<td><a href="/tags/tag_pre.asp">&lt;pre&gt;</a></td>
<td>定义预格式文本。</td>
</tr>
<tr>
<td>&lt;listing&gt;</td>
<td class="deprecated"><em>不赞成使用。</em>使用 &lt;pre&gt; 代替。</td>
</tr>
<tr>
<td>&lt;plaintext&gt;</td>
<td class="deprecated"><em>不赞成使用。</em>使用 &lt;pre&gt; 代替。</td>
</tr>
<tr>
<td>&lt;xmp&gt;</td>
<td class="deprecated"><em>不赞成使用。</em>使用 &lt;pre&gt; 代替。</td>
</tr>
</table>
<p>示例（i.用&lt;pre&gt;和&lt;code&gt;来写，要注意到&lt;code&gt; 元素不保留多余的空格和折行 ii.用&lt;var&gt;）</p>
i.
![image_1dftuoufdhtrm461gag25q1k8q2n.png-58.4kB][2]<br/>
![image_1dftuqjkoq87hfd1tlqecm1ik34.png-81.1kB][3]

ii.
![image_1dftut65c1m491n0rui1g4d1bu73h.png-37.3kB][4]
<br/>
<h4 style="text-align:center">4.引用、引用和术语定义</h4>
<table class="dataintable">
<tr>
<th style="width:30%">标签</th>
<th style="width:70%">描述</th>
</tr>
<tr>
<td><a href="/tags/tag_abbr.asp">&lt;abbr&gt;</a></td>
<td>定义缩写 或 首字母缩略语。</td>
</tr>
<tr>
<td><a href="/tags/tag_acronym.asp">&lt;acronym&gt;</a></td>
<td>定义首字母缩写 或 缩写。</td>
</tr>
<tr>
<td><a href="/tags/tag_address.asp">&lt;address&gt;</a></td>
<td>定义地址。（定义文档作者或拥有者的联系信息。）</td>
</tr>
<tr>
<td><a href="/tags/tag_bdo.asp">&lt;bdo&gt;</a></td>
<td>定义文字方向。</td>
</tr>
<tr>
<td><a href="/tags/tag_blockquote.asp">&lt;blockquote&gt;</a></td>
<td>定义长的引用。</td>
</tr>
<tr>
<td><a href="/tags/tag_q.asp">&lt;q&gt;</a></td>
<td>定义短的引用语。</td>
</tr>
<tr>
<td><a href="/tags/tag_phrase_elements.asp">&lt;cite&gt;</a></td>
<td>定义引用、引证、著作标题。</td>
</tr>
<tr>
<td><a href="/tags/tag_phrase_elements.asp">&lt;dfn&gt;</a></td>
<td>定义一个定义项目或缩略词。</td>
</tr>
</table>
<br/>
<h4 style="text-align:center">5.地址</h4>
用&lt;address&gt;标签，下面见示例
![image_1dftsh2ni17olcmj1d3d1a9u95lm.png-51.1kB][5]
<br/>
<h4 style="text-align:center">6.缩写(abbreviation)和首字母缩写（Acronym abbreviation）</h4>
缩写用&lt;abbre&gt;标签，首字母缩写用&lt;acronym&gt;标签
（其实这两者功能一样，可混用：都是在title属性中放要展示的完整版本内容，在开始标签、结束标签中间放缩写/首字母缩写内容）
下面见示例
![image_1dftt5q6k1tn714sj9c519dv1gmh1g.png-99.5kB][6]
<br/>
<h4 style="text-align:center">7.文字方向</h4>
用&lt;bdo&gt;标签 及 dir属性
![image_1dftt92ca1n5huci1av010gv1m891t.png-54.1kB][7]
<br/>
<h4 style="text-align:center">8.删除字效果和插入字效果</h4>
![image_1dfttg0d71o3n11abj391bua1meg2a.png-23.2kB][8]

### HTML链接

 






























  [1]: http://static.zybuluo.com/PenguinFather/nl3uihp7egu5irxxqqp9aitb/image_1dftv9b8justl2t5j616oao3l9.png
  [2]: http://static.zybuluo.com/PenguinFather/q37ng8omznpdv2is8exuiher/image_1dftuoufdhtrm461gag25q1k8q2n.png
  [3]: http://static.zybuluo.com/PenguinFather/ptemrbjajt1wh7ijbr8sdo08/image_1dftuqjkoq87hfd1tlqecm1ik34.png
  [4]: http://static.zybuluo.com/PenguinFather/v4k3pf979wml114twaql6qe5/image_1dftut65c1m491n0rui1g4d1bu73h.png
  [5]: http://static.zybuluo.com/PenguinFather/darz48vif29rc1enl6mh3z6h/image_1dftsh2ni17olcmj1d3d1a9u95lm.png
  [6]: http://static.zybuluo.com/PenguinFather/2ndtqok2vvcb72epzur3kh3w/image_1dftt5q6k1tn714sj9c519dv1gmh1g.png
  [7]: http://static.zybuluo.com/PenguinFather/gz2h3kbtcyysonhaxtpo940c/image_1dftt92ca1n5huci1av010gv1m891t.png
  [8]: http://static.zybuluo.com/PenguinFather/slf168ry725qqh5fp8cedzzy/image_1dfttg0d71o3n11abj391bua1meg2a.png