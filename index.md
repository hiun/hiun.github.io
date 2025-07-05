---
layout: home
title: Home
---

Hiun Kim is an ML engineer on the Naver Search team, working on machine learning for search models with vision and language technologies. Previously, he was an engineer on the Naver Clova team, where he worked on dialog systems, recommendation models, and generative models for local and e-commerce businesses in the East Asian market. Before that, he was an engineer on Naver’s Platform team, focusing on software engineering for web and serving systems.

{% assign focus_area = "These days my focus is on the topic of 1) machine learned (or symbolic) pattern prediction, 2) and applications of these for varying modalities and human activities (e.g. language, vision, sequences), 3) and leverage it to help people to understand our private and public world better, by cultivating, developing, and transferring information and support better. I wish the enhanced productivity originating from these can provide balanced opportunities, and promote equity in individuals, within societies, and between countries. Some related topics are Machine learning, Natural language processing, and Information retrieval." %}
{{ focus_area }}

You can visit my <a href="https://linkedin.com/in/hiun">LinkedIn</a> or <a href="https://github.com/hiun">GitHub</a>.


## papers

These are the papers among my works that I can share publicly (you can also try <a href="https://scholar.google.co.kr/citations?user=PdyEHY4AAAAJ&hl=en">Google Scholar</a>):


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

## misc

### Some ideas in my job:

First written in June 2025.

{{ focus_area }}

To this end, I wish to see a better information and support environment for people with the assistive systems at varying granularity of help (e.g. helps to explore, helps to find, or help by coaching, advising, or answering), utilizable cooperatively at people's unique time and space in their everyday life. I don't want to ignore the fact that technical research is not always an optimal solution for this, the assistance can be implementable by human systems instead of artificial systems, or fostering the economy, and so on. I think our obligations seem to advance assistive systems technologies to be usable as one of the best options for each society to implement better information and support environment, showing that potential seems one duty that researchers need to do. At the same time, I think we need to keep paying attention to current problems of information and support environment, and at the core, deficiencies of people at varying granularity of help in their everyday life across societies and countries.

Concerning the real world of cultivating, developing, and transferring information and support, I'd like to study and practice the development of information and support as energies and study better and healthier methods of transferring developed information and support energies from the source of users to the providing source, starting with related supply and demand development, ranging from the medium of "active" question answering to "passive" content exploration, or tailoring integration of services and tools while also taking public concerns into account.

### Some ideas for making improvements in my job:

First written in July 2025.

My hobby was used to reading management books about how private and public organizations make contributions in their field. I think many organizations that do things related to information and support share a timeless goal of helping people to understand their private and public worlds because that is what information and support can help. Before the digital era, languages, papers, newspapers, radios, or TVs were the great medium for that, in the digital era we have witnessed bidirectional communications infrastructure - the internet, and many websites on top of the internet, information retrieval systems for navigating these websites, question answering systems that just returns the answer, and intelligent virtual or physical assistant that provides information and various support. Just like computer architecture, the coarse layer in each needs its own research (e.g. linguistics (for language), mechanical engineering (for printing newspapers), electrical engineering (for radios, TVs, and internet infrastructure), mathematical and machine learning science (for information retrieval, QA systems, and intelligent agents)).

Currently, my focus is on the last layer of this information and support architecture, but as a researcher, I hope we can focus on things that don't change, such as helping people with information and support to understand the world, instead of focusing the current implementation of each coarse layer. For instance, to be freed at current implementation, I hope our research at each layer can be uniquely foundational to move forward to right future topics, but still fall into the broad topic of information and support for humans. I hope our study in each layer is conducted by leveraging innovations from the different scientific components in other layers or the same layer (I think well-known examples are, Information retrieval model in the web-scale collection and feedback, Representation learning model for Natural language processing, Using accelerator for greedy training of neural networks) to develop further.
