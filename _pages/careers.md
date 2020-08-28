---
layout: archive
title: "Careers"
permalink: /careers/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
[acdcd](https://aliceyu68.github.io/tongjie-yu.github.io/)
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
