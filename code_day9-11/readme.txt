//网页文字
/*第1个页面*/
Hello World

China is speeding up strategic plan, standards, traffic rules, laws and regulations on acci
dent-incurred liabilities for its smart car industry, Economic Information Daily reported 
Thursday.

Create Your Account
It is absolutely free

denis@getcraftwork.com        Create your password                 Sign Up


/*第2个页面 图标文字解说*/
Boatloads of Awesome

Ready-made, customizable, HTML 
landing page sections

① Mobile First
All modulz are built mobile-first for maximum 
device compatibil

② Accessibility
Support for IE8, mobile and tablet devices, screenrea
ders and color blind.

③ Fluid Typography
On different screen sizes, fonts automagically 
scale with the viewpoint

④ Customization
Make any design your own using the Style Editor. Per
sonalize fonts, colors, and layouts to create the custom 
look you want.


/*第3个页面*/
Supportive policies 
for China's smart car

China will come up with its own smart car stan
dards, traffic rules, laws and regulations relating to 
safety, according to the China Industry Innovation 
Alliance for the Intelligent and Connected 
Vehicles.

Check out Features         Try product for Free
右侧是图片


/*第4个页面*/
Try Our Awesome Products

Li Jun, a China Academy of Engineering academician and also director of the alliance's experts' committee, said that China will also launch design guidance for smart cars, smart map architecture and standards for test grounds.

Li said the smart car industry is able to enlarge the current car industry by 1 trillion yuan ($158.15 billion) and also able to boost fast development in 5G, internet of cars, big data, artificial intelligence and new-energy vehicles.

Zhang Junyi, a partner with NIO Capital, said that the smart car is the trend for the car industry and China's auto sector will usher in a new key development stage with the improvement of infrastructure, technology, policies and laws.
the  viewport.


/*第5个页面*/
左图右字
Learn How to Improve Your Personal Business

Li Jun, a China Academy of Engineering academician and also director of the alliance's experts' committee, said that China will also launch design guidance for smart cars, smart map architecture and standards for test grounds.

右图左字
Choose Between Two Beautifully Designed Color Schemes

China will come up with its own smart car standards, traffic rules, laws and regulations relating to safety, according to the China Industry Innovation Alliance for the Intelligent and Connected Vehicles.


/*第6个页面*/
Our Awesome Crew
Our unique online teaching style makes learning easy for everyone. Whether you are trying to land a new job, brush up on your skills.
下四个图
鼠标hover 样式： 
Ethan Dutton
Senior Visual Designer（大写）


/*第7个页面*/
//左侧
Fell free to Write Us（大写）
E-mail
Subject
Message
Send（大写）

//右侧
Contacts
Make any design your own using the Style Editor. Personalize fonts, colors, and layouts to create the custom look you want.
地址（图标） 360 King Street Feastrvale Trevose, PA 19057  
电话（图标） (755) 564-84-12
邮箱（图标） youname@mail.com


/*第8个页面 footer*/
① Learn More（大写）
How it works? 
Meeting tools 
Live streaming 
Contact method

② About Us（大写）
About us 
Features 
Privacy police 
Terms & Conditions

③ Support（大写）
F.A.Q. 
Contact us 
Live chat 
Phone call 

④ Enjoy your Life（大写）
Great web UI kit for designers, freelancers or business.
图标


//知识点
①background: url('../images/showcase.jpg') no-repeat 0 -400px;

②css如何实现鼠标移至图片上显示遮罩层及文字
<div class="img_div">
<img src="./images/page6/people1.png">
<a href="#">
<div class="mask">
<h3>Ethan Dutton</h3>
<span>Senior Visual Designer</span>
<div class="page6_img">
<img src="./images/page6/1.png">
<img src="./images/page6/2.png">
<img src="./images/page6/3.png">
</div>
</div>
</a>
</div>

.mask {
opacity: 0;
}
mask样式外层加<a href="#"></a>
.img_div a:hover .mask {
    opacity: 1;           
}    //.img_div是整个元素的样式，.mask是遮罩层

③input 
输入提示：   placeholder
去掉默认背景框：   border: none;
圆角边框：   border-radius: 3px;

④margin: auto;    让块级元素水平居中            margin: 52px 200px 68px 200px;

⑤color: rgba(255, 255, 255, 0.2);    第四个值越小，透明度越低

⑥text-transform:uppercase;  大写
letter-spacing: 3px; 字间距
font-weight  定义由粗到细的字符。400 等同于 normal，而 700 等同于 bold。100-900
montserrat extralight

⑦background-color: transparent; 透明

⑧flex
任何一个容器都可以指定为Flex布局。
flex-wrap: wrap;           如果一条轴线排不下，如何换行。wrap：换行，第一行在上方。
.box {
  justify-content: flex-start | flex-end | center | space-between | space-around;
}
flex-start（默认值）：左对齐
flex-end：右对齐
center： 居中
space-between：两端对齐，项目之间的间隔都相等。
space-around：每个项目两侧的间隔相等。所以，项目之间的间隔比项目与边框的间隔大一倍。

⑨img 透明度
img
{
  opacity:0.4;
  filter:alpha(opacity=40); /*  IE8 及其更早版本 */
}

