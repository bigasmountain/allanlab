---
title: "News"
layout: textlay
excerpt: "Yamazaki Lab at IIS U-Tokyo"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
