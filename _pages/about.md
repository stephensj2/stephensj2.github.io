---
permalink: /
title: "Welcome!"
excerpt: #"About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

You have stumbled upon the webpage of a Jon Stephens. As this name is not uncommon, I will provide some information to more uniquely identify myself. I am a Computer Science Ph.D. student at the University of Texas at Austin (UT) where I am a member of the [UToPiA](http://utopia.cs.utexas.edu/) group and advised by its fearless leader, [Işıl Dillig](http://www.cs.utexas.edu/~isil/). My research interests include program analysis/verification, synthesis and security. Prior to UT, I received a BS and MS in Computer Science from the University of Arizona where I was advised by [Saumya Debray](https://www2.cs.arizona.edu/people/debray/).

Recent Publications
-----

<ul class="pub_list">
{% assign filtered = site.publications | reverse %}
{% for post in filtered limit:3 %}
  {% capture pub %} {% include pub_list.html %} {% endcapture %} <li> {{ pub | strip_newlines }}
{% endfor %}
