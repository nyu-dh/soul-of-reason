---
layout: page
title: People
menubar: people_menu
permalink: /people
# hero_darken: true
show_sidebar: false
hero_height: is-fullwidth
---

## Project Team

(In alphabetical order)

{% for member in site.data.team %}
**{{ member.name }}**  
{{ member.title }}
{% endfor %}  

### Contact

Get in touch by emailing us at **{{ site.email }}**.
