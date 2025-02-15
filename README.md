

# Student Reports

<ul>
  {% for thing in site.pages %}
    {% if thing.identifier == 'course-index' %}
  <li>
    <a href="{{ thing.url }}">{{ thing.title }}, {{ thing.block }}</a>
  </li>
  {% endif %}
  {% endfor %}
</ul>