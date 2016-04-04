---
layout: article
title:  "收银流程"
date: 2015-11-10 13:46:52
categories: portfolio
summary: 改版收银流程主要是加了订单的概念，为以后电商之路做好准备。
promote: images/03tou-sylc.jpg
icon: images/03tijiaodingdan.jpg
---
<br><br>
夺宝与全价购买设计成一套收银流程，但根据使用场景等分析后，最终设计成不公用购物车及一起付款，而要分开付款。


{% assign maintitle = '头脑风暴' %}
{% include article_maintitle.html%}

* <span class="article_subtitle">使用场景</span>  <br />
<div class="article_right_img">
	<img src="{{ site.baseurl }}/images/03tounaofengbao.jpg" alt="头脑风暴" >  	
</div>
用户B：夺宝用户，平常闲的没事就夺夺宝，看到可以全价购买了，但不想购买，还是想要多宝。<br>
用户A：购物用户，很想要某件商品，看到有夺宝的功能尝试了几下，没有中最终决定全价购买。<br>

<br><br><br><br><br><br><br><br>

{% assign maintitle = '收银流程' %}
{% include article_maintitle.html%}

<img src="{{site.baseurl}}/images/03shouyinliuchengtu.jpg" alt="收银流程图"> 

* <span class="article_subtitle">思考过程</span>  <br />
考虑到毕竟是要渐渐变成一个购物类网站，收银流程也应该按照购物类来说，后台需要锁库存，还是需要有一个订单的概念。
最终设计是全价购买和一元夺宝分别走两个付款流程。思考过放在一个购物车内，可以一起付款，但是由于实现起来会比较繁琐，且程序有难度，最终被否掉。

{% assign maintitle = '交互设计' %}
{% include article_maintitle.html%}
<div class="article_left_img">
	提交订单
	<img src="{{ site.baseurl }}/images/03tijiaodingdan.jpg" alt="提交订单" >  
	
</div>
<div class="article_right_img">
	支付订单
	<img src="{{ site.baseurl }}/images/03dingdanzhifu.jpg" alt="订单支付" >  
	
</div>

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

* <span class="article_subtitle">主要改动</span>  <br />
①现有的模式：没有订单的说法。<br>
②改版后：支付流程是：确认订单【去结算】--->订单页【去支付】（此时已生成订单）--->支付页【立即支付】。



{% assign maintitle = '整个项目心得' %}
{% include article_maintitle.html%}

有时候做设计会作死，单单想着界面该放哪些元素，该怎么放却忽略了交互本质。
最开始要先确定项目目标，设计目标，再去确定主流程，次要流程。想好流程，再根据流程设计界面，就会快很多，且清晰很多，
若一个页面不知道该怎么做的时候，想一想使用场景，思考用户使用流程，用户目标这些就会明了很多。
<br><br><br>
