---
layout: archive
title: "Other"
permalink: /other/
author_profile: true
---

{% include base_path %}

Sometimes when I'm not doing research I get the opprotunity to make things, usually out of wood. Here are a few of those things.

{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}

