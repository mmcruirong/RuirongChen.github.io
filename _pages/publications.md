---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{}}">my Google Scholar profile</a>.</u>
{% endif %}

{% https://scholar.google.com/citations?hl=en&user=N-NBveMAAAAJ %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
