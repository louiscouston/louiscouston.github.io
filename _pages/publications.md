---
layout: archive
title: "Peer-Reviewed Publications"
permalink: /publications/
author_profile: false
---

Click on each title to visit the publisher's listing of a paper.
You can also find our articles (as well as conference abstracts) on [Google Scholar](https://scholar.google.co.uk/citations?user=orC_dKIAAAAJ&hl=fr&oi=ao){:target="_blank"}.

{% include base_path %}

{% for post in site.publications reversed %} 
  {% include archive-publications.html %} 
{% endfor %}

# White papers

{% for post in site.whitepapers reversed %}{% include archive-publications.html %}{% endfor %}

# Other publications

{% for post in site.otherpublications reversed %}{% include archive-publications.html %}{% endfor %}

