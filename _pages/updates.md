---
layout: page
title: Project Updates
permalink: /updates
# hero_darken: true
show_sidebar: false
hero_height: is-fullwidth
---

{% for item in site.updates %}
- <b>[{{ item.title }}]({{ item.url | absolute_url }})</b>  
published by {{ item.author }} on {{ page.date | date: '%B %d, %Y' }}
{% endfor %}
