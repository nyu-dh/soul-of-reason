---
layout: page
title: Raising the Volume!
subtitle: People
menubar: people_menu
permalink: /people
---

## Project Team

(In alphabetical order)

{% for member in site.data.team %}
**{{ member.name }}**  
{{ member.title }}
{% endfor %}  

### Contact

Get in touch by emailing us at **{{ site.email }}**.
