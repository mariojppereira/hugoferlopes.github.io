---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from: 
  - /wordpress/academic-papers/
---

You can also find my articles on <u><a href="https://scholar.google.pt/citations?user=vK-y0CYAAAAJ&hl=pt-PT">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
