---
layout: archive
title: "Conferences"
permalink: /conferences/
author_profile: true
---

{% for post in site.conferences reversed %}
  {% include archive-single-conference.html %}
{% endfor %}