---
layout: home
title: Home
---

<img src="/s/img/profile-linkedin-dist-20250730.jpeg" class="profile-img">

Hiun Kim is a research engineer at Naver Search and Clova team, where he focuses on machine learning, natural language processing, and information retrieval. Previously, he was a software engineer at Naver’s platform team.

I am broadly interested in studying an advanced information-based environment that can help.

<!--
Hiun Kim is an ML engineer on the Naver Search team, working on machine learning for search models with vision and language technologies. Previously, he was an engineer on the Naver Clova team, where he worked on dialog systems, recommendation models, and generative models for local and e-commerce businesses in the East Asian market. Before that, he was an engineer on Naver’s Platform team, focusing on software engineering for web and serving systems.
-->

You can visit my <a href="https://linkedin.com/in/hiun">LinkedIn</a> or <a href="https://github.com/hiun">GitHub</a>.


## papers

These are the papers among my works that I can share publicly (you can also try <a href="https://scholar.google.co.kr/citations?user=PdyEHY4AAAAJ&hl=en">Google Scholar</a>):

{% for paper in site.data.papers %}
<b>{{ paper.subject }}</b>
<p>{{ paper.authors }}</p>
<i>{{ paper.venue }}. {{ paper.date }}.</i>
<p>{% if paper.link %}{{ paper.link }}.{% endif %}</p>
{% endfor %}



## patents

{% for paper in site.data.patents %}
<b>{{ paper.subject }}</b>
<p>{{ paper.authors }}</p>
<i>{{ paper.venue }}</i>
<p>{% if paper.link %}{{ paper.link }}.{% endif %}</p>
{% endfor %}



## misc

{% for data in site.categories.notes %}
  <p><a href="{{ data.url }}">{{ data.title }}</a>&nbsp;<span style="color: gray; font-size: 0.9em"> {{ data.date | date: "%b %d, %Y" }}</span></p>
{% endfor %}
