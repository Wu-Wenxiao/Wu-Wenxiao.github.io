---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if 1 %}
  You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=z52QyJUAAAAJ&hl=zh-CN).
{% endif %}

<p>&#9841; indicates equal contributions, * indicates corresponding author.</p>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
