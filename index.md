---
layout: home
title: Home
---
ML/SW Engineer, NAVER
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


<b>Research Interests:</b> <br />
Information Retrieval, Natural Language Processing <br />

<b>Industrial Experience:</b> <br />
Search, RecSys, Ads, Media, Communications <br />

<b>Employment:</b> <br />
&bull; ML/SW Engineer, NAVER (2017 ~ Present) <br />
&bull; Co-Founder & SW Engineer, Divtag (2014-2016)<br />


<b>Education:</b> <br />
&bull; BS in CSE, Sejong University (SJU) (2014-2018)<br />
&bull; NLP (company supported graduate program), KAIST (2020)<br />

<!--
<div style="margin-top: 0.5em;"></div>
Essay: <br />
{%- for data in site.categories.essay -%}
&bull; <a href="{{ data.url }}">{{ data.title }}</a> &nbsp;<span style="color: gray; font-size: 0.9em"> {{ data.date | date: "'%y-%m" }}</span><br />
{% endfor %}
<div style="margin-bottom: 0.5em;"></div>
-->

<!--
<p>&bull; I'd like to achieve better economic, and social results through this work.</p>
<p>&bull; I'd like to have purposeful studies, and experiences for this goal. :)</p>
-->
<!--publications-->
<div style="margin-top: 2.5em;"></div>
<p class="subtitle">Publications:</p>
{% for paper in site.data.papers %}
<p>
<b>{{ paper.subject }}</b> <br>
<span>{{ paper.authors }}</span> <br>
<i>{{ paper.venue }}</i> <br>
Link: {{ paper.link }}<br>
</p>
{% endfor %}
<!--
<p><i style="color: gray;"><a href="/pubs">more &raquo;</a></i></p>
-->




<div style="margin-top: 2.5em;"></div>
<p class="subtitle">Patents:</p>
{% for pa in site.data.patents %}
<p>
<b>{{ pa.subject }}</b> <br>
<span>{{ pa.authors }}</span> <br>
<i>{{ pa.venue }}</i> <br>
Link: {{ pa.link }}<br>
</p>
{% endfor %}




<!--talks-->
<div style="margin-top: 2.5em;"></div>
<p class="subtitle">Presentations:</p>
{% for pr in site.data.talks %}
<p>
<b>{{ pr.title }}</b> <br>
{% if pr.venue %}
  <i>{{ pr.venue }}</i>,
{% endif %}
<span>{{ pr.date }}</span> <br>
Link: {{ pr.link }}<br>
</p>
{% endfor %}
<!--
<p><i style="color: gray;"><a href="/talks">more &raquo;</a></i></p>
-->

