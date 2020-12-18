---
layout: page
title: Project Updates
permalink: /updates
# hero_darken: true
show_sidebar: false
hero_height: is-fullwidth
---

{% for item in site.updates %}
- [{{ item.title }}]({{ item.url | absolute_url }}) by {{ item.author }}
{% endfor %}
