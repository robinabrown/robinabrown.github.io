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

## Preprints
{% for post in site.preprints reversed %}
  {% include archive-single-paper.html %}
{% endfor %}

## Publications
{% for post in site.publications reversed %}
  {% include archive-single-paper.html %}
{% endfor %}
