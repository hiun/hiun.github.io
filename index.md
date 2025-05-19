---
layout: home
title: Home
---

Hiun Kim is an ML engineer on the Naver Search team, working on machine learning for search models with vision and language technologies. Previously, he was an engineer on the Naver Clova team, where he worked on dialog systems, recommendation models, and generative models for local and e-commerce businesses in the East Asian market. Before that, he was an engineer on Naver’s Platform team, focusing on software engineering for web and serving systems.

His research and industrial interests lies in practicing the development of information products or energies, and studying better methods of transferring developed information products or energies from the energy source of users to the energy source of providers, starting with related supply and demand development, ranging from the medium of "active" question answering to "passive" content consumption, while also taking public concerns into account.

You can visit my <a href="https://linkedin.com/in/hiun">LinkedIn</a> or <a href="https://github.com/hiun">GitHub</a>.

## papers

Here is the list of papers based on some of my work (you can also try <a href="https://scholar.google.co.kr/citations?user=PdyEHY4AAAAJ&hl=en">Google Scholar</a>):


<ol>
{% for paper in site.data.papers %}
<li>
{{ paper.authors }}. {{ paper.subject }}. {{ paper.venue }}. {{ paper.date }}. {% if paper.link %}{{ paper.link }}.{% endif %}
</li>
{% endfor %}
</ol>


## patents

<ol>
{% for paper in site.data.patents %}
<li>
{{ paper.authors }}. {{ paper.subject }}. {{ paper.venue }}. {{ paper.link }}.
</li>
{% endfor %}
</ol>
