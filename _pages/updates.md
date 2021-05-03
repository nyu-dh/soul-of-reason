---
layout: page
title: Project Updates
show_sidebar: false
hero_height: is-fullwidth
---
<div class="columns is-multiline unset-gradient">
  {% assign updates = site.updates | sort: 'date' | reverse %}
  {% for item in updates %}
  <div class="column is-4-desktop is-6-tablet">
    {% assign author = site.data.authors[item.author] %}
    <a href="{{ item.url | absolute_url }}">
      <div class="card update-card">
        {% if item.img %}
          <div class="card-image image is-3by2" alt="{{ item.title | strip_html }}" style="background-image:url('{{ item.img | absolute_url }}');background-position:center;"></div>
        {% endif %}
        <div class="card-content">
          <p class="title is-4 mb-3 gradient mb-6">{{ item.title }}</p>
          <p class="subtitle is-6"><b>Published by {{ author.name | default: 'Project Team' }}</b><br>
          <time datetime="{{ item.date | date: '%B %d, %Y' }}">{{ item.date | date: '%B %d, %Y' }}</time></p>
          <p>
            {% if item.abstract %}
            {{ item.abstract | markdownify }}
            {% else %}
            {{ item.content | markdownify | strip_html | truncatewords: 25 }}
            {% endif %}
          </p>
        </div>
      </div>
    </a>
  </div>
  {% endfor %}
</div>
