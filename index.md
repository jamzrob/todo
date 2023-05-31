---
layout: default
title: Todo
---

<ul>
  {% for p in site.pages %}
    {% if p.url contains "23" %}
      <li>
        <a href="/todo{{ p.url }}">{{ p.url }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>
