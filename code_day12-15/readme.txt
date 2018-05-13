//文字
/*left2*/
menu
Overview   Sales   Your Staff   Analytics & Targeting   What’s New
 
Your Products
Books   Tutorials   Stocks   Infographics

Dashboard
Messages   Connections   Integrations   Account Settings   App Settings

Monthly Goals

/*header*/
Messages
Jordan J.
Administrato

I pay for the 4Mb/sec down, 512 Kb/sec up service from O2. In fact, it's relatively quick, and stable...

Victor Weber
I shared this on my fb wall a few months back, and I thought I'd share it here again because it's such a great...

If there is anyone who needs an invitation please add yourself in the comments of this post!

BruteDC is a peer-to-peer movie+tv series sharing and downloading platform which works on intranet inside...

Sally Willis
Twitter
Yes, it's O2: 'internet extreme', which is no longer offered.

Robert Patton
A Team
I change my service from this 4Mb plan to their much cheaper 8Mb plan, my speed will dramatically decrease.


//网页信息

/*left1*/
background-color:  #1d2531;
图标大小      60px × 60px
图标1      #2ca0f6  
图标2      #9581e3
图标3      #f05034
图标4      #1d2531 

/*left2*/
background-color:  #222c3c;
提示     蓝 #279cf4
           红 #e24023
占用比例 #9582e3


//知识点
①css 自适应浏览器高度
让竖在左侧的导航可以呈现自适应的高度
#menu{
    position:fixed;
    display:block;
    left:0;
    top:0;
    bottom:0;
    width:200px;
    background-color:black;
}



②section
拿报纸举个例子：一份或一张报纸有很多个版块，有头版、国际时事版块、体育版块、娱乐版块、文学版块等等，像这种有版块标题的、内容属于一类的版块就可以用section包起来。然后在各个版块下面，又有很多文章、报道，每篇文章都有自己的文章标题、文章内容。这个时候用article就最好。如果一篇报道太长，分好多段，每段都有自己的小标题，这时候又可以用section把段落包起来。



<header>
    <nav>导航</nav>
</header>

<section>
<header>页面主要区域的顶部</header>
<article><h1>文章1</h1><p>内容1</p></article>
<article><h1>文章2</h1><p>文章2</p></article>
<footer>页面主要区域底部信息</footer>
</section>

<aside>广告?</aside>
<aside>热点新闻连接?</aside>

<footer>页面底部区域</footer>

section是页面的主要内容。

    不要简单地将section用作样式化钩子。将div和span用作该目的。
    如果header、footer、aside或article在语义上更加适合你的内容，则不要使用section
    不要使用section，除非它自身有一个标题


③css 添加图片按钮
.btn1{background:url(btn_bg.png)}
要先定义按钮大小


④进度条
https://codepen.io/yuxiaoliu6/pen/errxZz


⑤button           http://www.runoob.com/tags/att-button-type.html
input                 http://www.runoob.com/tags/tag-input.html


⑦相对浏览器固定位置
fixed    
生成绝对定位的元素，相对于浏览器窗口进行定位。
元素的位置通过 "left", "top", "right" 以及 "bottom" 属性进行规定。


⑧:before 选择器
在被选元素的内容前面插入内容。
使用 content 属性来指定要插入的内容。



