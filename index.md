---
layout: home
title: Home
---

<!--
REPLACE PERCENT to %
{PERCENT include profile.html PERCENT}
-->

Hiun Kim (김희언)

Email: hiunkim.me [at] gmail.com <br />
<a href="https://linkedin.com/in/hiun">[LinkedIn]</a>
<a href="https://scholar.google.com/citations?hl=en&user=PdyEHY4AAAAJ&view_op=list_works&sortby=pubdate">[Google Scholar]</a>
<a href="https://dblp.org/pid/204/0565.html">[DBLP]</a>

## positions

Naver (Dec. 2017 - Present)
- Information Systems


<br/>

<!--
Hiun Kim is an ML engineer on the Naver Search team, working on machine learning for search models with vision and language technologies. Previously, he was an engineer on the Naver Clova team, where he worked on dialog systems, recommendation models, and generative models for local and e-commerce businesses in the East Asian market. Before that, he was an engineer on Naver’s Platform team, focusing on software engineering for web and serving systems.
-->

## papers



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


<!--
## personal

[some work focuses]

I am broadly interested in exploring, understanding, and advancing the intrinsic mechanisms and interactional effects of language-based systems that support human-leading informational tasks, including their understudied long-tail generality, methods, and ecosystemic issues.

Aiming for they to have the potential to be more viable and diversely helpful at scale in the future by studying, planning, and improving the helpfulness of the results in their ad-hoc and longer time-frame informational tasks.

Personally, with this, I expect a more equitable world.

I think focusing can be important, but generally, I’d like to prevent research and development activities from being kept bound to particular approaches or consensus understandings, as that can do work right, but does not always lead to the right work.
-->


## misc

[daily log](/notes)

<!--
[독후감 (book memos)](/bookmemo)

{% for data in site.categories.notes %}
  <p><a href="{{ data.url }}">{{ data.title }}</a>&nbsp;<span style="color: gray; font-size: 0.9em"> {{ data.date | date: "%b %d, %Y" }}</span></p>
{% endfor %}
-->
































