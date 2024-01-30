---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

2024
======
* S. J. B. Yoo, S. K. Singh, M. B. On, G. Gul, G. S. Kanter, R. Proietti and P. Kumar. Quantum Wrapper Networking. IEEE Communications Magazine. January 2024.
<u><a href="[DOI](https://ieeexplore.ieee.org/document/10384627)">DOI</a>.</u>


*  



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
