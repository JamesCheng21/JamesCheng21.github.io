---
layout: page
title: 
subtitle: 
cover-img:
- "/assets/img/4M7A3580.jpg"
---

<div style="border-left: 4px solid #007acc; padding: 12px; background: #f5faff; margin: 20px 0;">
I'll join the University of Hong Kong as a tenure-track assistant professor in the Department of Civil Engineering in Fall 2026. I am recruiting multiple fully funded PhD and postdoctoral positions in <b>sustainable building energy systems, decision-oriented digital twins, and low-carbon AI infrastructure</b>. <a href="/hire">More details here >></a>
</div>


I am a Postdoctoral Associate at MIT Building Technology, working on sustainable and intelligent building energy systems using data-efficient computational methods. With over a decade of multi-continental research experience, I develop scalable, decision-oriented digital twins to address scientific and practical challenges in the transition to zero-carbon cities. <a href="/aboutme">More about me >></a><br>

<h3>Research</h3>

My research sits at the intersection of building energy systems and computational technologies, aiming both to unlock the potential of smart buildings to <em>accelerate urban energy transition</em> and to develop <em>sustainable AI infrastructure</em> as an integral component of future cities. <a href="/research">More about research >></a><br>

<h3>News</h3>
<ul>
{% for item in site.data.news limit: 15 %}
  <li>
    <strong>{{ item.date }}</strong> - {{ item.text }}
    {% if item.url %}
      <a href="{{ item.url | relative_url }}">[more]</a>
    {% endif %}
  </li>
{% endfor %}
</ul>
<a href="/news">Older news >></a>