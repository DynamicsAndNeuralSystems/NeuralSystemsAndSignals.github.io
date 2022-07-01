---
title: "News"
layout: textlay
excerpt: "Dynamics and Neural Systems Lab at The University of Sydney."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
