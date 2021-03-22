---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

![Image of 7ipwom](http://yilerat19.github.io/images/7iPWOM_banner.png)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
