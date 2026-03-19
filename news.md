---
layout: page
title: 
subtitle: 
---

<h3>News</h3>
<ul>
{% for item in site.data.news %}
  <li>
    <strong>{{ item.date }}</strong> - {{ item.text }}
    {% if item.url %}
      <a href="{{ item.url | relative_url }}">[more]</a>
    {% endif %}
  </li>
{% endfor %}
</ul>
<p><a>Updates since summer 2025.</a></p>