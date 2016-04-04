---
layout: article
title: "测脸测财运活动"
summary: 一个上传照片测财运，分享拿红包的活动交互设计
date: 2016-01-28 13:46:52
categories: portfolio
promote: images/05tou-cl.jpg
icon: images/05icon.jpg

---
<br><br>

上传照片流程中不要为难用户，让用户分享时也要让其是有意愿主动分享的。


{% assign maintitle = '活动经验' %}
{% include article_maintitle.html%}


* <span class="article_subtitle">游戏类型</span>  ： 测脸测财运活动。
* <span class="article_subtitle">获得经验</span>  <br />
（1）上传照片时的交互<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;例如，采用进度条的方式，且最开始直接前进到80%处，再慢慢加载。用户等待时间不可超过3秒。<br />
（2）后台照片识别的规则<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①只要检测到鼻子眼睛嘴就可以给出分数，不要在乎大小，亮度，位置。即使是动物脸也可以测财运。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;②当第一次上传不成功，再次上传时不管上传什么照片都应该给出结果。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;③每1分钟允许有一次不识别。<br />
（3）不同进度，不同流程。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①流程一：第一次进入，走完整正常流程。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;②流程二：测试过，有结果，但是没有拿红包。再进来看到结果，直接分享可拿红包。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;③流程三：已经拿过红包，再次测试（此时已经无法再次获得红包）。<br />
（4）B通过A的界面进入到游戏的流程<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;由于B是新用户，此时的目的不是宣传夺宝，而是引导用户去玩，拿到红包之后自然会想去了解这个红包的用途。所以在B玩游戏时不要打扰，可以在点点滴滴渗透夺宝，不要再游戏一开始就想着介绍。<br />
（5）对于分数结果页会有的情况罗列：<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;①正常流程的页面<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;②已经拿过红包的页面（没有拿红包的按钮入口了）。<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;③分享出去后，别人点进来看到的页面。（我也要测按钮）<br />
（5）出错页面的统一展示。<br />



{% assign maintitle = '设计过程' %}
{% include article_maintitle.html%}

* <span class="article_subtitle">玩游戏领红包思考流程</span><br>
1.没玩过的正常流程。<br>
2.领过红包的重玩流程。<br>
3.别人通过分享进来的流程。<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;其中1.2要注意能让用户轻松找到红包以及了解夺宝，还有就是尽量投入在游戏。<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3要注意一开始看到的页面不要有广告，而是尽可能吸引用户去玩<br><br />




<div class="article_left_img">
	活动流程图<br>	<br>
	<img src="{{ site.baseurl }}/images/05flowchart.jpg" alt="活动流程图" >  	
</div>



<div class="article_right_img">
	上传照片页面<br>
	<img src="{{ site.baseurl }}/images/05interface1.jpg" alt="上传照片页面" >  	
</div>


<div class="article_right_img">
	分数结果页面<br>
	<img src="{{ site.baseurl }}/images/05interface2.jpg" alt="分数结果页面" >  	
</div>

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

{% assign maintitle = '数据相关' %}
{% include article_maintitle.html%}


* <span class="article_subtitle">数据统计</span> 

|         | 参与侧脸总人数           | 参与分享拿红包  |
| ------------- |:-------------:| -----:|
| 总人数      | 141046 | 28169 |
| 微信人数      | 88992      |   19205 |
| App人数 | 52054      |    8964 |
| 上传照片总数     | 325157 |  |
| 微信中重复照片      | 46301      |    |
| 获得财运照片      | 194838      |    |
| 满5减1用户 |       |    14170 |
| 满10减2用户 |       |    13999 |

<br>

* <span class="article_subtitle">数据反思及经验</span>  <br />
1.根据数据可以看出来，这次活动的参与程度一般，可能是春节很少人关注的原因。<br>
2.对于分享来说，是参与人数的19%左右.可能用户主动分享的意愿较低，以后要转换思路，多突出有利益获得让其分享。<br>
3.微信参与与分享的人数均高于app，说明还是有一定量的新用户参与其中。说明活动吸引用户程度还算可以，只是从老用户分享出去的较少。<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;对于这部分，之前一味地想着拉新，却忽略了老用户分享出去的少，再想着拉新都是多余的，<br><br>
所以以后要干脆直接从活动开始就要告诉老用户可以获得红包。




<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
