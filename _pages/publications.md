---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

1. **Zhang Z**, Gao Q, Ren X, et al. <a href="https://www.cell.com/the-innovation/fulltext/S2666-6758(23)00110-8">Characterization of intratumor microbiome in cancer immunotherapy[J].</a> *The Innovation*, 2023, 4(5).
2. 
