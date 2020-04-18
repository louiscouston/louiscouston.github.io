---
layout: archive
title: "Peer-Reviewed Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [Google Scholar](https://scholar.google.co.uk/citations?user=orC_dKIAAAAJ&hl=fr&oi=ao){:target="_blank"}.

{% include base_path %}

{% for post in site.publications reversed %}{% include archive-publications.html %}{% endfor %}

# Other Publications
{% for post in site.publications reversed %}{% include archive-publications.html %}{% endfor %}
