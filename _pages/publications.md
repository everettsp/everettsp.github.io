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



{% assign posts_sorted = site.publications | sort: "date" %}
{% for post in posts_sorted %}
  {% include archive-single.html %}
{% endfor %}
