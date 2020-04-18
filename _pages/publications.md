---
layout: archive
title: "Peer-Reviewed Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [Google Scholar](https://scholar.google.co.uk/citations?user=orC_dKIAAAAJ&hl=fr&oi=ao){:target="_blank"}.

Other Publications

{% include base_path %}

{% for post in site.publications if post.collection == 'otherpublications' %}{% include archive-publications.html %}{% endfor %}

{% include base_path %}

{% for post in site.publications reversed if post.collection == 'publications' %}{% include archive-publications.html %}{% endfor %}

