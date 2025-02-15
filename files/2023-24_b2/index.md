---
title: DS Course
block: AY 2023-24 Block 2
identifier: course-index
---

<ul>
  {% for thing in site.pages %}
    {% if thing.identifier == 'ay-2023-24-b2' %}
  <li>
    <a href="{{ thing.url }}">{{ thing.title }}</a>
  </li>
  {% endif %}
  {% endfor %}
</ul>
