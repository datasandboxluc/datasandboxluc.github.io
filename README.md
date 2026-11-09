

# Student Reports

<ul>
  {% assign courses = site.pages | where: "identifier", "course-index" | sort: "block" | reverse %}
  {% for thing in courses %}
    {% if thing.identifier == 'course-index' %}
  <li>
    <a href="{{ thing.url }}">{{ thing.title }}, {{ thing.block }}</a>
  </li>
  {% endif %}
  {% endfor %}
</ul>