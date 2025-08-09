---
layout: home
title: Home
---

<!-- <details> <summary>click for the picture</summary> -->
<img src="/s/img/profile-linkedin-dist-20250801.jpeg" class="profile-img">
<!-- </details> -->

Hiun Kim is a research engineer at Naver Search and Clova team, where he focuses on machine learning, natural language processing, and information retrieval. Previously, he was a software engineer at Naver’s platform team.

I do not try to have a research interest bound to specific technical methods or approaches in the longer time frame.

I am broadly interested in exploring, understanding, and advancing intrinsic mechanisms and interactional effects of understudied information-based systems and environments, so that they can have the potential to be more viable and helpful at scale in the future.

Personally, with this, I expect a more equitable world.

<!--
Hiun Kim is an ML engineer on the Naver Search team, working on machine learning for search models with vision and language technologies. Previously, he was an engineer on the Naver Clova team, where he worked on dialog systems, recommendation models, and generative models for local and e-commerce businesses in the East Asian market. Before that, he was an engineer on Naver’s Platform team, focusing on software engineering for web and serving systems.
-->

You can visit my <a href="https://linkedin.com/in/hiun">LinkedIn</a> or <a href="https://github.com/hiun">GitHub</a>.

My email is hiunkim.me [at] gmail.com

## papers

These are the papers among my works that I can share publicly (you can also try <a href="https://scholar.google.co.kr/citations?user=PdyEHY4AAAAJ&hl=en">Google Scholar</a>):

{% for paper in site.data.papers %}
<span style="font-weight:bold">{{ paper.subject }}</span>
<span>{{ paper.authors }}</span>
<span style="font-weight:italic">{{ paper.venue }}. {{ paper.date }}.</span>
{% if paper.link %}<span>{{ paper.link }}</span>{% endif %}
<br/>
{% endfor %}



## patents

{% for paper in site.data.patents %}
<span style="font-weight:bold">{{ paper.subject }}</span>
<span>{{ paper.authors }}</span>
<span style="font-weight:italic">{{ paper.venue }}</span>
{% if paper.link %}<span>{{ paper.link }}</span>{% endif %}
<br/>
{% endfor %}



## misc

{% for data in site.categories.notes %}
  <p><a href="{{ data.url }}">{{ data.title }}</a>&nbsp;<span style="color: gray; font-size: 0.9em"> {{ data.date | date: "%b %d, %Y" }}</span></p>
{% endfor %}



