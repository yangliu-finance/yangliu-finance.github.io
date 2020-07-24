---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

[Choosing Factors: Explanatory Power vs Model Parsimony](https://yangliu-finance.github.io/files/WorkingPaper.pdf)
这里是Research页顶部的内容，下面的内容是在 `_publications` 目录下，按MarkDown语法规则写内容即可，[MarkDown语法教程看这里](http://xianbai.me/learn-md/article/about/readme.html)

`_pages\research.md` 中下面这些代码不要动
```
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

```

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
