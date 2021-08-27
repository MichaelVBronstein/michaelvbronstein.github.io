---
title: "News"
layout: textlay
excerpt: "Michael V Bronstein"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
<a href="{{ article.link.url }}">{{ article.link.display }}

{% endfor %}
