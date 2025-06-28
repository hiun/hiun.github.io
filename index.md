---
layout: home
title: Home
---

Hiun Kim is an ML engineer on the Naver Search team, working on machine learning for search models with vision and language technologies. Previously, he was an engineer on the Naver Clova team, where he worked on dialog systems, recommendation models, and generative models for local and e-commerce businesses in the East Asian market. Before that, he was an engineer on Naver’s Platform team, focusing on software engineering for web and serving systems.

He is broadly interested in the topic of 1) machine learned (or symbolic) pattern prediction, 2) and applications of these for varying modalities and human activities (e.g. language, vision, sequences), 3) and leverage it for better information mediation. He is also interested in helping cultivate better information. Some related topics are Machine learning, Natural language processing, and Information retrieval.

Concerning the real world of information mediation, I'd like to study and practice the development of information products as energies and study better and healthier methods of transferring developed information energies from the source of users to the source of providers, starting with related supply and demand development, ranging from the medium of "active" question answering to "passive" content exploration, while also taking public concerns into account.

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
