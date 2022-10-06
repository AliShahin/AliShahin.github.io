---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Google Scholar](https://scholar.google.com/citations?user=1kVnWYwAAAAJ&hl=en)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
