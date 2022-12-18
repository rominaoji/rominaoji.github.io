---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from:
  - /experience
---

<p> 
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=tcOO28oAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
</p>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
