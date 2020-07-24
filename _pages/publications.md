---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Download Abstracts](https://yangliu-finance.github.io/files/zdinakmg_abstract.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
