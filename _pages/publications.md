---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

2024


2023


2022
2021
2019
2017


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
