---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if author.googlescholar %} -->
  <!-- You can also find my articles on <u><a href="{{https://dblp.org/pers/hd/h/Huang:Hongyao}}">my dblp profile</a>.</u> or <u><a href="{{https://scholar.google.com/citations?hl=en&user=BDOpOLkAAAAJ}}">my Google Scholar profile</a>.</u> -->
<!-- {% endif %} -->

You can also find my articles on **[dblp]**(https://dblp.org/pers/hd/h/Huang:Hongyao) and **[Google scholar]**(https://scholar.google.com/citations?hl=en&user=BDOpOLkAAAAJ)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
