---
layout: home
title: Home
---

Hiun Kim is an ML engineer on the Naver Search team, working on machine learning for search models with vision and language technologies. Previously, he was an engineer on the Naver Clova team, where he worked on dialog systems, recommendation models, and generative models for local and e-commerce businesses in the East Asian market. Before that, he was an engineer on Naver’s Platform team, focusing on software engineering for web and serving systems. His interests are in studying better matching and processing methods for the long-tail demands of users, service providers, and public concerns.

You can visit my <a href="https://linkedin.com/in/hiun">LinkedIn</a> or <a href="https://github.com/hiun">GitHub</a>.

## papers

Here is the list of papers based on some of my work (you can also try <a href="https://scholar.google.co.kr/citations?user=PdyEHY4AAAAJ&hl=en">Google Scholar</a>):



{% for paper in site.data.papers %}
<p>
{{ paper.authors }}. {{ paper.subject }}. {{ paper.venue }}. {{ paper.date }}. [LINK].
</p>
{% endfor %}



## patents

{% for paper in site.data.patents %}
<p>
{{ paper.authors }}. {{ paper.subject }}. {{ paper.venue }}. {{ paper.date }}. [LINK].
</p>
{% endfor %}
