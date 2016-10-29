-----------------------------语义化标签-----------------------------------
+结构标签
###body标签###
 body 元素定义文档的主体。
  body 元素包含文档的所有内容（比如文本、超链接、图像、表格和列表等等。
  <body>
    内容... ...
  </body>
 
###head标签###
可告知浏览器其自身是一个 HTML 文档。
 <head>
  <title>文档的标题</title>
  </head>
  定义和用法
 <head> 标签用于定义文档的头部，它是所有头部元素的容器
### html标签###
  <html>
    <head>
      这里是文档的头部 ... ...
      ...
    </head>
    <body>
      这里是文档的主体 ... ...
      ...
    </body>
</html>
<html>

### meta标签
定义页面的描述信息,便于搜索优化
<meta name="keywords" content="HTML,ASP,PHP,SQL">
<meta charset="UTF-8">

###  title标签
title可定义文档的标题。
  <head>
    <title>欢迎来到github</title>
  </head>

###  link标签
   没有结束标签。 引入一个外部样式表
<head>
<link rel="stylesheet" type="text/css" href="index.css" />
</head>

### style标签
  引用内联样式
  <div style="color:#000"></div>
  <head>
    <style type="text/css">
      h1 {color:red}
      p {color:blue}
    </style>
  </head>
  
 ### script标签
 定义内联或外联的脚本，如JS。
    <script src="http://www.my97.net/dp/My97DatePicker/WdatePicker.js" type="text/javascript"></script>
    或<script> var i =1 ; console.log(i)</script>


+行内标签
 ### a标签### 
 实现超链接。title属性的作用，鼠标滑过链接文字时会显示这个属性的文本内容					
 <a href="http://www.baidu.com" title="百度">百度</a>
 ### img标签
  img 元素向网页中嵌入一幅图像。
  注意，<img> 标签并不会在网页中插入图像，而是从网页上链接图像。<img> 标签创建的是被引用图像的占位空间。
  <img> 标签有两个必需的属性：src 属性 和 alt 属性
  <img src="/images/flow.jpg"  alt="人物" />

###span标签
无语义，常用内联容器，定义文本内区块
span 没有固定的格式表现。当对它应用样式时,才会产生效果

### em i标签
  em em是emphasize(强调) 标签中的文本表示为强调的内容，对于所有浏览器的显示效果来说，是把这段文字用斜体来显示
  i 斜体文本,告诉浏览器将包含其中的文本以斜体字（italic）或者倾斜（oblique）字体显示；
  
###strong、b标签
 默认情况下它们起的均是加粗字体的作用
　 首先，从语义上来说<b>是UI层面上的‘加粗’，而<strong>是语气上的强调\加重。
  strong标签和 <em> 标签一样，用于强调文本，但它强调的程度更强一些。
  b标签是基于内容的样式标签

### br 标签
 可在文档中插入换行符。
<br> 标签是空标签（意味着它没有结束标签，因此这是错误的：<br></br>）

### sub、sup标签
<sub> 标签定义下标文本。下标文本将会显示在当前文本流中字符高度的一半为基准线的下方，但是与当前文本流中文字的字体和字号都是一样的。下标文本能用来表示化学公式，比如 H2O。
这是 <sub>下标</sub>
这是 <sup>上标</sup>

### del标签
文档中已删除的文本，<del> 和 <ins> 一起使用，描述文档中的更新和修正。
<p>My favorite color is <del>blue</del> <ins>red</ins>!</p>

### textarea标签
  定义多行的文本输入控件。
  文本区中可容纳无限数量的文本，其中的文本的默认字体是等宽字体（通常是 Courier）。
  <textarea rows="3" cols="20">
  内容......
  </textarea>

### label标签
为input 元素定义标注（标记）
<label for="ss"><input id="ss" type="checkbox" />文本</label>

#### 块标签####
###div 标签
  无语义。 可定义文档中的分区或节
  标签可以把文档分割为独立的、不同的部分。它可以用作严格的组织工具，并且不使用任何格式与其关联。
 
### p 标签
文章段落
p 元素会自动在其前后创建一些空白。浏览器会自动添加这些空间

### <h1>-<h6> 标签
文章标题，并且依据重要性递减。 <h1> 是最高的等级
<h1>这是标题 1</h1>
<h2>这是标题 2</h2>
<h3>这是标题 3</h3>
<h4>这是标题 4</h4>
<h5>这是标题 5</h5>
<h6>这是标题 6</h6>

### ul 标签
无序列表。ul+li可以替换表格的作用，具体的设置，如果宽度高度、行间距、背景边框等需要配合CSS一起设置。
<ul>
  <li>a</li>
  <li>b</li>
</ul>

### ol 标签
有序列表。
<ul>
  <li>a</li>
  <li>b</li>
</ul>

### dl、 dt 、dd 标签
自定义列表
  < dt>< /dt>和< dd>< /dd>都必须放在< dl>< /dl>标志对之间。
  <dl>
  <dt>列表标题</dt>
  <dd>列表内容</dd>
  <dd>列表内容</dd>
  ...
  </dl> 
### form 标签
<form> 标签用于为用户输入创建 HTML 表单 
<form action="" method="get">
  <input type="submit" value="Submit" />
</form>

### table 标签
 一行一列

<table border="1">
<caption> 元素定义表格标题</caption>
  <thead >
    <tr>
      <th>姓名</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>张三</td>
    </tr>
  </tbody>
</table>
 tr 元素定义表格行，th 元素定义表头，td 元素定义表格单元
 <caption>定义表格的标题，必须直接放置到 <table> 标签之后
<thead></thead>表头。当打印过长的表格时，表头会出现在分页上。

<tfoot></tfoot>表脚。当打印过长的表格时，表脚会出现在分页上。

<tbody></tbody>表格主体、正文。thead、tfoot和tbody需一起使用。

cellpadding设置单元格边框与单元格里的内容之间的距离。

cellspacing设置单元格间的距离。

colspan设置表格中的行跨越多列列数

+ html5新增标签

之前用div来表示页面章节，但是这些div都没有实际意义。（即使我们用css样式的id和class形容这块内容的意义）。这些标签只是我们提供给浏览器的指令，
只是定义一个网页的某些部分。但现在，那些之前没“意义”的标签因为因为html5的出现消失了，这就是我们平时说的“语义”。

### header元素
header 元素代表“网页”或“section”的页眉。
通常包含h1-h6元素或hgroup，作为整个页面或者一个内容块的标题。也可以包裹一节的目录部分，一个搜索框，一个nav，或者任何相关logo。
<header>
    <hgroup>
        <h1>网站标题</h1>
        <h1>网站副标题</h1>
    </hgroup>
</header>

###footer元素
<footer>
    版本信息
</footer>
可以是“网页”或任意“section”的底部部分；
没有个数限制，除了包裹的内容不一样，其他跟header类似。

### hgroup元素### 
hgroup元素代表“网页”或“section”的标题，当元素有多个层级时，该元素可以将h1到h6元素放在其内，譬如文章的主标题和副标题的组合
<hgroup>
    <h1>这语义化标签</h1>
    <h2>HTML 5</h2>
</hgroup>

如果只需要一个h1-h6标签就不用hgroup
如果有连续多个h1-h6标签就用hgroup
如果有连续多个标题和其他文章数据，h1-h6标签就用hgroup包住，和其他文章元数据一起放入header标签

### nav元素
元素代表页面的导航链接区域。用于定义页面的主要导航部分。
<nav>
    <ul>
        <li>1</li>
        <li>2</li>
        <li>3</li>
    </ul>
</nav>

### aside元素
元素被包含在article元素中作为主要内容的附属信息部分，其中的内容可以是与当前文章有关的相关资料、标签、名次解释等

<article>
    <p>内容</p>
    <aside>
        <h1>简介</h1>
        <p>我是。。。。</p>
    </aside>
</article>

article元素之外使用作为页面或站点全局的附属信息部分。最典型的是侧边栏，其中的内容可以是日志串连，其他组的导航，甚至广告，这些内容相关的页面

aside在article内表示主要内容的附属信息，
在article之外则可做侧边栏，没有article与之对应，最好不用。
如果是广告，其他日志链接或者其他分类导航也可以用

### section元素
元素代表文档中的“节”或“段”，“段”可以是指一篇文章里按照主题的分段；“节”可以是指一个页面里的分组。
section通常还带标题，虽然html5中section会自动给标题h1-h6降级，但是最好手动给他们降级。
一张页面可以用section划分为简介、文章条目和联系信息。不过在文章内页，最好用article。section不是一般意义上的容器元素，如果想作为样式展示和脚本的便利，可以用div。
<section>
    <h1>section是啥？</h1>
    <article>
        <h2>关于section</h1>
        <p>section的介绍</p>
        <section>
            <h3>关于其他</h3>
            <p>关于其他section的介绍</p>
        </section>
    </article>
</section>
### article元素
article元素最容易跟section和div容易混淆，其实article代表一个在文档，页面或者网站中自成一体的内容，其目的是为了让开发者独立开发或重用。譬如论坛的帖子，博客上的文章，一篇用户的评论，一个互动的widget小工具。（特殊的section）
<article>
    <h1>一篇文章</h1>
    <p>文章内容..</p>
    <footer> </footer>
</article>
