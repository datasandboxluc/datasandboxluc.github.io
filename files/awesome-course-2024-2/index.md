---
title: Awesome Course
block: Spring 2024
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