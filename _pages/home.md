---
title: "Can Bu (卜灿) - Homepage"
layout: gridlay
excerpt: "Can Bu"
sitemap: false
permalink: /
---

<div id="top"></div>
<div class="container-fluid">
<div class="row">
<div class="col-sm-8">

### **About <font color="#00d1ff">Me</font>**
<!-- <a href ="https://small-volcano.github.io/allnews"> <img align="left" src="{{ site.url }}{{ site.baseurl }}/images/Eagle.png" class="img-responsive" width="35%"  /> </a> -->
I come from Xuzhou, Jiangsu, China, where is known as 'Qiangu dragon enclave, a generation of emperor Township'. I am currently pursuing the M.S degree of Nanjing Normal University(NNU), Nanjing, China. Before that, I received bachelor's degree in Huaiyin Institute of Technology(HYIT).

My research interests include:
human activity recognition
federated learning
deep learning
machine Learning<br>

<!-- By the way, I must express my gratitude to <a href="https://sci-hub.se/alexandra">Alexandra Elbakyan</a>. The website built by her helps me much on paper writing and search.
Everyone can find the papers they need <a href="https://sci-hub.st/">here [Sci-Hub]</a>. -->
<br>

<!-- ### **Notice**
在尝试联系我前请阅读这个<a href="https://small-volcano.io/document">文档</a>。 -->
<!-- <del>Select the part inside the arrow to reveal the hidden content.</del> -->

<!-- <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?w=128&d=Xit1o4P9tPO4V5F-vf13Il6mKflR-sERYSPiKcWoLcM"></script> -->

<!-- ### **Skills & Hobbies (Sort by Proficiency)**

#### **Skills**
* Languages
    - Python (PyTorch, Jittor, Keras, TensorFlow).
	- C++, LaTeX.
	- SQL.


### **CV**
You can download my latest CV ([English Version](https://wenbohuang1002.github.io/papers/Wenbo Huang's CV.pdf) and [Chinese Version](https://wenbohuang1002.github.io/papers/黄文博的简历.pdf)).<br>
CV was last updated on June 30, 2022.<br>
<!-- <pre>
                            CV was last updated on October 25, 2021.
　　　　　／＞＿＿＿フ       
　　　　　|  　_　 _|   
　 　　　／  ミ  ˇ ノ  
　　 　 /　　　 　 |
　　　 /　 ヽ　　 ﾉ
　 　 │　　|　|　|
　／￣|　　 |　|　|
　| (￣ヽ＿_ヽ_)__)
　＼二つ
</pre> -->

<!-- ### **News**
{% for article in site.data.news limit:8 %}
{{ article.date }} :
<em>{{ article.headline }}</em>
{% endfor %}
#### <a href="{{ site.url }}{{ site.baseurl }}/allnews">[See All News]</a>
#### <a href="#top">[Go Back to Top]</a> -->

</div>

<div class="col-sm-4" style="display:table-cell; vertical-align:middle; text-align:center">

  <ul style="overflow: hidden">
  <a href ="{{ site.url }}{{ site.baseurl }}/experience"> <img src="{{ site.url }}{{ site.baseurl }}/images/adminR.jpg" class="img-responsive" width="100%" /></a>
  </ul>

  <!-- <br clear="all" /> -->
<!-- 
  Can Bu (卜灿)<br>  
  211189, College of Electrical and Automation Engineering, Xianlin Campus (<a href="https://j.map.baidu.com/fd/EeA">Maps</a>).<br>  
  <a href="http://www.njnu.edu.cn/">Nanjing Normal University (NNU)</a> <br>  
  Nanjing, Jiangsu, China. <br>  

  <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=00acff&w=268&t=tt&d=Xit1o4P9tPO4V5F-vf13Il6mKflR-sERYSPiKcWoLcM&ct=000000&co=ffffff&cmo=f87d00&cmn=00ff10'></script> -->
  <!-- <a href="{{ site.url }}{{ site.baseurl }}/treasures"><font color="white">All failures are my treasures.</font></a> <br> --> 
</div>

</div>
</div>

<div class="col-sm-12">

### **Publications (<font color="red">Journal Papers</font> <font color="green">&</font> <font color="blue">Conference Papers</font>)**

<!-- #### * means corresponding authors -->

{% for publi in site.data.publist limit:100 %}

<div class="col-sm-11 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="200px" style="float: left" />

 <p>{{ publi.description }}</p>

 <p><em>{{ publi.authors }}</em></p>

 <p>{{ publi.venue }}</p>

 <p>{{ publi.name }}</p>

 <p>{{ publi.DOI }}</p>

 {% if publi.number_link == 1 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 2 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 3 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 4 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]
 [<a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 5 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]
 [<a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>]
 [<a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 6 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]
 [<a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>]
 [<a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a>]
 [<a href="{{ publi.link6.url }}">{{ publi.link6.display }}</a>]</p>
 {% endif %}

 </div>
</div>

{% endfor %}

<br clear="all"/>

#### <a href="{{ site.url }}{{ site.baseurl }}/publications">[See All Publications]</a>

</div>

<div class="col-sm-12">

#### <a href="#top">[Go Back to Top]</a>

### **Theses**

{% for publi in site.data.theseslist limit:6 %}

<div class="col-sm-11 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="200px" style="float: left" />

 <p>{{ publi.description }}</p>

 <p><em>{{ publi.authors }}</em></p>

 <p>{{ publi.venue }}</p>

 <p>{{ publi.name }}</p>

 <p>{{ publi.DOI }}</p>

 {% if publi.number_link == 1 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 2 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 3 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 4 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]
 [<a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 5 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]
 [<a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>]
 [<a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a>]</p>
 {% endif %}

 {% if publi.number_link == 6 %}
 <p>[<a href="{{ publi.link1.url }}">{{ publi.link1.display }}</a>]
 [<a href="{{ publi.link2.url }}">{{ publi.link2.display }}</a>]
 [<a href="{{ publi.link3.url }}">{{ publi.link3.display }}</a>]
 [<a href="{{ publi.link4.url }}">{{ publi.link4.display }}</a>]
 [<a href="{{ publi.link5.url }}">{{ publi.link5.display }}</a>]
 [<a href="{{ publi.link6.url }}">{{ publi.link6.display }}</a>]</p>
 {% endif %}

 </div>
</div>

{% endfor %}

<p> &nbsp; </p>

</div>

#### <a href="#top">[Go Back to Top]</a>

### **Academic Related**
<!-- 
#### **Academic Service**
* **Journal Reviewer**
	- <a href="https://benthamscience.com/journals/current-computer-aided-drug-design">Current Computer-Aided Drug Design</a>, 2022.
    - <a href="https://www.mdpi.com/journal/sensors">MDPI Sensors</a>, 2021.

* **Conference Reviewer**
	- <a href="http://www.icctis.org/ ">International Conference on Computer Technology and Information Science (CITS 2023)</a>, 2023.
    - <a href="http://www.csaeconf.org/">ACM The 6th International Conference on Computer Science and Application Engineering (CSAE 2022)</a>, 2022, <a href="https://wenbohuang1002.github.io/papers/CSAE2022 Certificate of Appreciation_Wenbo Huang.pdf">Certificate</a>.
	- <a href="http://www.icoice.org/">International Conference on Optoelectronic Information and Computer Engineering (OCIE 2022)</a>, 2022.
	
* **Book Reviewer**
    - Book entitled--'Digital Innovation Adoption: Architectural Recommendations and Security Solutions', 2022.

* **Teaching Activity**
	- Teaching assistant of Edu-By: The Time of Robotics - Artificial Intelligence and Social Change (博雅课：机器人时代 - 人工智能与社会变革), Fall 2021, Nanjing Normal University.
	- Teaching assistant of Artificial Intelligence and Big Data, Spring 2022, Nanjing Normal University.
	- Security Administrator for the Institute of Information and Control Technologies, School of Electric and Autumation Engineerning, 2020-2021, Nanjing Normal University. -->

#### **Award & Honor**
* **Scholarship**
    - National Scholarship, Ministry of Education of China, 2019 (Top 0.2% in HYIT).

* **Competition** 
    - The 18th Huawei Cup Graduate Student Mathematical Modeling Competition, 2021,Third Prize
    - The 19th Huawei Cup Graduate Student Mathematical Modeling Competition, 2022,Third Prize

<!-- * **Honor**
	- National Scholarship, Ministry of Education of China, 2019 (Top 0.2% in HYIT)
	- The 18th Huawei Cup Graduate Student Mathematical Modeling Competition, 2021,Third Prize
    - The 19th Huawei Cup Graduate Student Mathematical Modeling Competition, 2022,Third Prize -->


#### <a href="#top">[Go Back to Top]</a>

### **Research Partners (Partial)**
<!-- <div style="clear:both"></div> 每六个人后便需要加这句 -->
#### **Supervisors**
<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/leizhang.jpg"/>
<p style="text-align: center;"> <a href="http://leizhangnjnu.github.io">Lei Zhang</a></p>
</div>

<div style="clear:both"></div>

#### **Instructors**
<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/junhe.jpg"/>
<p style="text-align: center;"> <a href="https://sites.google.com/site/hejunzz/">Jun He</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/haowu.jpg"/>
<p style="text-align: center;"> <a href="https://www.researchgate.net/profile/Hao-Wu-19">Hao Wu</a></p>
</div>

<!-- <div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/fuhongmin.jpg"/>
<p style="text-align: center;"> <a href="https://www.researchgate.net/profile/Fuhong-Min">Fuhong Min</a></p>
</div> -->

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/aiguosong.jpg"/>
<p style="text-align: center;"> <a href="https://scholar.google.com/citations?hl=zh-CN&user=RjQ5TrEAAAAJ">Aiguo Song</a></p>
</div>

<div style="clear:both"></div>

#### **Friends**

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/qiteng.jpg"/>
<p style="text-align: center;"> <a href="https://github.com/tengqi159">Qi Teng</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/kunwang.jpg"/>
<p style="text-align: center;"> <a href="https://github.com/KennCoder7">Kun Wang</a></p>
</div>
<!-- <div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/zhenyuwang.jpg"/

</div> -->

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/yintang.jpg"/>
<p style="text-align: center;"> <a href="https://yinntag.github.io/">Yin Tang</a></p>
</div>

<!-- <div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/tianyiliu.jpg"/>
<p style="text-align: center;"> <a href=" ">Tianyi Liu</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/wenbingao.jpg"/>
<p style="text-align: center;"> <a href="https://scholar.google.com/citations?user=ggPvJNgAAAAJ&hl=zh-CN">Wenbin Gao</a></p>
</div> -->

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/xingwang.jpg"/>
<p style="text-align: center;"> <a href="https://chauncey-wang.github.io/">Xing Wang</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/chaoleihan1.jpg"/>
<p style="text-align: center;"> <a href="https://chaolei98.github.io/">Chaolei Han</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/shuoyuanwang.jpg"/>
<p style="text-align: center;"> <a href="https://claydon-wang.github.io/">Shuoyuan Wang</a></p>
</div>





</div> -->

<div style="clear:both"></div>

#### <a href="#top">[Go Back to Top]</a>

