---
layout: page
title: 
subtitle: 
cover-img:
- "/assets/img/4M7A3580.jpg"
---

<div style="border-left: 4px solid #007acc; padding: 12px; background: #f5faff; margin: 20px 0;">
I'll join the University of Hong Kong as a tenure-track assistant professor in the Department of Civil Engineering in Fall 2026. I am recruiting multiple fully funded PhD and postdoctoral positions in sustainable urban energy systems, decision-oriented digital twins, and low-carbon AI infrastructure. <a href="/hire">More details here >></a>
</div>


I am a Postdoctoral Associate at MIT Building Technology, working on sustainable and intelligent urban energy systems using data-efficient computational methods. With over a decade of multi-continental research experience, I develop scalable, decision-oriented digital twins to address scientific and practical challenges in the transition to zero-carbon cities. <a href="/aboutme">More about me >></a><br>

<h3>Research</h3>


Enabled by the rapid expansion of sensing and data infrastructure, AI and machine-learning methods are increasingly used to improve how buildings are designed and operated, reducing energy use while maintaining comfort and functionality. At the same time, the rapid growth of AI has drawn attention to the soaring energy demand of data centers, which places increasing pressure on electricity grids and contributes to rising carbon emissions. Beyond improving data center efficiency alone, new opportunities are emerging at the interface between AI infrastructure and the built environment, including closer integration between data centers and surrounding buildings to enable energy sharing and carbon reduction. This talk introduces example applications from both sides of this interaction, highlighting key challenges and emerging opportunities in using AI and the built environment together to address climate challenges.

<a href="/research">More about research >></a><br>

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