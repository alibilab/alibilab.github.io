---
title: "Algorithmic Biology Lab - News"
layout: textlay
excerpt: "Algorithmic Biology Lab at UCSF."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
