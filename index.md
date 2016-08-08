---
title: Data Test
layout: default
---
# Things I Know

Testing different ways to represent collections of things in Jekyll.

<ul>
{% for thing in site.things %}
  <li>
    <a href="{{ thing.url }}">{{ thing.title }}</a>
  </li>
{% endfor %}
</ul>
