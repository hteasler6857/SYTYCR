---
title: "Hello World"
layout: "base.njk"
templateEngineOverride: njk,md
---

this is a home page.
Eat it jack hole
Another thing that

## Markdown


## Articles 
<ul>
{% for article in collections.articles %}
<li><a href="{{ article.url }}">{{ article.data.title }} </li>
{% endfor %}
</ul>