---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

Currently, it is a bit empty, but I am working on filling this page with some exciting research.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
