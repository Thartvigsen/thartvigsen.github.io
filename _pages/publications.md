---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

Publication Summary: (conference: number of papers)

KDD: 2, AAAI: 1, ACL: 1, CIKM: 1, IEEE BigData: 3, HEALTHINF: 2, URTC: 2, IEEE BHI: 1, ECML: 1

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

