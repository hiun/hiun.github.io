---
layout: home
title: Home
---
Software / Machine Learning Engineer, NAVER
<p>
<a href="https://linkedin.com/in/hiun">[linkedin]</a>&nbsp;&nbsp;
<a href="https://github.com/hiun">[github]</a>&nbsp;&nbsp;
<a href="https://scholar.google.co.kr/citations?user=PdyEHY4AAAAJ&hl=en">[google scholar]</a>&nbsp;&nbsp;
</p>


🌎 Projects: <br />
&bull; <a href="https://search.naver.com/search.naver?sm=tab_hty.top&where=image&query=%EC%84%9C%EC%9A%B8&oquery=%EC%84%9C%EB%B9%84%EC%8A%A4">Web Image Search</a> / ML (22-Present) <br />
&bull; <a href="https://shopping.naver.com/">E-Commerce Search&RecSys</a> / ML (21-22) <br />
&bull; <a href="https://clova.ai/ko/platform/">Model Serving Platform</a> / Backend (20-21) <br />
&bull; <a href="https://clova.ai/aicontactcenter">Contact Center AI</a> / Backend&ML (19-20) <br />
&bull; <a href="#">User Feedback Platform</a> / Backend&Frontend (17-19) <br />
&bull; <a href="https://ece.unist.ac.kr/">UNIST ECE</a> / Systems (16) <br />
&bull; <a href="https://divtag.sejong.edu/">Divtag</a> / Backend&Frontend (14-16) <br />
&bull; <a href="#">Partner</a> / Backend (14) <br />
&bull; <a href="https://eng.sejong.ac.kr">SEJONG U</a> / CSE (14-18) <br />

😃 My interests: <br />
&bull; I am interested in the process of producing and managing information. <br />
&bull; I'd like to know more about people who are in the process of getting something, and people who are in the circumstance of communicating something. <br />
&bull; More specifically, I am interested in services, businesses, or technology to help users better connect and communicate with their wanted products and services. <br />
&bull; Topics include search services, recommendation services, and advertising services. <br />

<!--
<p>&bull; I'd like to achieve better economic, and social results through this work.</p>
<p>&bull; I'd like to have purposeful studies, and experiences for this goal. :)</p>
-->
<!--publications-->
<div style="margin-top: 2.5em;"></div>
<p class="subtitle">📚 publications</p>
{% for paper in site.data.papers %}
<p>
<b>"{{ paper.subject }}"</b> <br>
<span>by {{ paper.authors }}</span> <br>
In <i>{{ paper.venue }}</i>, <span>{{ paper.date }}</span> <br>
Link: {{ paper.link }}<br>
</p>
{% endfor %}
<!--
<p><i style="color: gray;"><a href="/pubs">more &raquo;</a></i></p>
-->



<!--talks-->
<div style="margin-top: 2.5em;"></div>
<p class="subtitle">⭐ talks & misc.</p>
{% for pr in site.data.talks %}
<p>
<b>"{{ pr.title }}"</b> <br>
{% if pr.venue %}
  In <i>{{ pr.venue }}</i>,
{% endif %}
<span>{{ pr.date }}</span> <br>
Link: {{ pr.link }}<br>
</p>
{% endfor %}
<!--
<p><i style="color: gray;"><a href="/talks">more &raquo;</a></i></p>
-->

