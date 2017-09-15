<h1>-<h6>：标题
<p>：段落
<body>：html文档的主体
<html>：定义整个html文档
<br>：定义换行
<a>(<a href="link">)：链接
<img src="img.jpg", width="width", height="height">：图像
<hr />添加水平线
不使用utf-8字符集会出现中文字符乱码，可使用<head>标签修改content中charset为utf-8
html属性：以键值对形式出现
举例：居中标题<h1 align="center">
	背景颜色<body color="yellow">
	表格边框<table border="1">
块级元素的前后都会有一个额外的空行，无论是否手动添加
<!--this is a comment>添加注释

<center>,<font>,<basefont>,<s>,<strike>,<u>,<align>,<bgcolor>,<color>等标签和属性已经被废弃，新的html标准建议使用样式代替

样式实例：

背景颜色
<body style="background-color:yellow">
<h1 style="background-color:red">this is a heading</h1>
<p style="background-color:blue">this is a paragraph</h2>
</body>

字体，颜色和尺寸
font-family:verdana;color:red;font-size:20px

文本对齐
style="text-align:center"

文本格式化标签：
<b>粗体文本
<big>大号字
<em>着重文字
<i>斜体字
<small>小号字
<strong>加重语气
<sub>下标字
<sup>上标字
<ins>插入字
<del>删除字
<u>

计算机输出标签
<code>计算机代码
<kbd>键盘码
<samp>计算机代码样本
<tt>打字机代码
<var>变量定义
<pre>预格式文本

引用及术语定义
<abbr>缩写
<acronym>首字母缩写
<address>地址
<bdo>文字方向
<blockquote>长的引用
<q>短的引用
<cite>引用、引证
<dfn>定义项目

样式表：
外部样式表：应用到多个页面的样式规定
内部样式表：应用到单个页面的样式规定

命名锚
<a name="label">锚</a>
举例：
文档创建书签
<a name="tips">注意事项</a>
同一文档指向该锚的链接
<a href="#tips">注意事项</a>
其他页面指向该锚的链接
<a href="http://www.baidu.com#tips">注意事项</a>

插入图像：
图像标签<img>源属性Src
<img src="url"/>
替换文本属性alt
<img src="url"alt="textfiled">
网页背景
<body background="url">
调整图片排列方式使用align属性
使用width和height属性调整图片大小
将图片作为链接
<a href="url"><img border="0" src="url"/></a>
