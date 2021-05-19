---
layout: page
title: People
menubar: people_menu
show_sidebar: false
hero_height: is-fullwidth
---
## Contact

Get in touch by emailing us at **{{ site.email }}**.

## Project Team

(In alphabetical order)

### Current

{% for member in site.data.team.current %}
**{{ member.name }}**  
{{ member.title }}
{% endfor %}  

### Past

{% for member in site.data.team.past %}
**{{ member.name }}**  
{{ member.title }}
{% endfor %}  
