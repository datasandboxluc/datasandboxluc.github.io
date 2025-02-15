---
title: DS Course
block: AY 2023-24 Block 2
identifier: course-index
---

<ul>
  {% for thing in site.pages %}
    {% if thing.identifier == 'ac-2024-1' %}
  <li>
    <a href="{{ thing.url }}">{{ thing.title }}</a>
  </li>
  {% endif %}
  {% endfor %}
</ul>
