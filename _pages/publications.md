---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on <u><a href="{{https://scholar.google.co.uk/citations?user=orC_dKIAAAAJ&hl=fr&oi=ao}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-publications.html %}
{% endfor %}
