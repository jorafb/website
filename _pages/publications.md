---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="https://scholar.google.ca/citations?user=eMPV_ZkAAAAJ"><i class="fa fa-fw fa-google-plus-square" aria-hidden="true"></i>Prof. Jing Yuan's Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
