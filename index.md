---
layout: home
title: Home
---
SW/ML Engineer, NAVER
<p>
<a href="https://linkedin.com/in/hiun">[linkedin]</a>&nbsp;&nbsp;
<a href="https://github.com/hiun">[github]</a>&nbsp;&nbsp;
<a href="https://scholar.google.co.kr/citations?user=PdyEHY4AAAAJ&hl=en">[google scholar]</a>&nbsp;&nbsp;
</p>

<!--
소스 전반 확인 하고 일단 배포.


**블로그 글 관련 내용
블로그 글 넣기 (gpt 관련, transformer 관련)
블로그 글 다듬기
블로그 글 제목에 한글, 영문 병기.
~마크다운 렌더링 더 수월하게 만들기 (지금 gpt 블로그 글 인덴테이션등 깊고, 글씨 크기도 차이나고 좀 이상함..)~
~모바일에서 잘 보이는지 다시 한번 보기.~


v gitignore 추가
배포, 클라우드플레이 설정
코드 및 전반적으로 확인 하고 배포
(링크 컨텐츠, 소스 등 전반적으로 괜찮은지..)

여행 블로그 글 복원? 검토.
-->

<div style="margin-top: 0.5em;"></div>
✏️ Essay: <br />
{%- for data in site.categories.essay -%}
&bull; <a href="{{ data.url }}">{{ data.title }}</a> &nbsp;<span style="color: gray; font-size: 0.9em"> {{ data.date | date: "'%y-%m" }}</span><br />
{% endfor %}
<div style="margin-bottom: 0.5em;"></div>

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
&bull; Designing and studying intelligent systems for information activities - models, evaluations, humans, society. <br />
&bull; Information retrieval (IR), Natural language proc. (NLP), Computer vision (CV), Language models (LLMs). <br />

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

