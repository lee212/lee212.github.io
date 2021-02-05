---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find a full list of my articles on <u><a href="https://scholar.google.com/citations?user=28RS60IAAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Recent publications
======================


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
