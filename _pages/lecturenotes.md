---
layout: archive
title: "Lecture notes"
permalink: /lecturenotes/
author_profile: true
---

{% include base_path %}

{% for post in site.lecturenotes reversed %}
  {% include archive-single.html %}
{% endfor %}
