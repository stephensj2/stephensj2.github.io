---
permalink: /
title: "Welcome!"
excerpt: #"About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

You have stumbled upon my 

Recent Publications
-----

<ul class="pub_list">
{% for post in site.publications limit:3 reversed %}
  {% capture pub %} {% include pub_list.html %} {% endcapture %} <li> {{ pub | strip_newlines }}
{% endfor %}
