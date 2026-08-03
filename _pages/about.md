---
permalink: /
title: "Jiyou Shin (신지유)"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Ph.D. candidate in the [Robotics and Intelligent System Engineering Lab (RISE Lab)](https://rise.skku.edu) at Sungkyunkwan University (SKKU), supervised by Prof. Hyungpil Moon. I received my Bachelor's degree from SKKU. My research interests include robotic manipulation, force control, vision-language-action (VLA) models, and diffusion policies.

For publications and further information, please visit my [Google Scholar profile]({{ site.author.googlescholar }}).

Publications
======

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
