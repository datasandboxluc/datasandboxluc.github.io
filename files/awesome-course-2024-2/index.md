---
title: DS Course
block: AY 2024-25 Block 3
identifier: course-index
---

<ul>
  {% for thing in site.pages %}
    {% if thing.identifier == 'ac-2024-2' %}
  <li>
    <a href="{{ thing.url }}">{{ thing.title }}</a>
  </li>
  {% endif %}
  {% endfor %}
</ul>
