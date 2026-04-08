---
permalink: /
title: ""
excerpt: "Computational Psycholinguistics, Language Acquisition, and NLP"
author_profile: true
---

I study how humans and language models learn, process, and generalize language.

My work connects cognitive science, second language acquisition, and machine learning to build human-grounded models of language behavior and better ways to evaluate language technology.

[CV (PDF)](/files/cv.pdf)

## News

{% for item in site.data.news %}
- **{{ item.date }}**: {% if item.url %}[{{ item.text }}]({{ item.url }}){% else %}{{ item.text }}{% endif %}
{% endfor %}
