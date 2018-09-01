---
permalink: /
title: "Welcome!"
excerpt: #"About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

You have stumbled upon the webpage of a Jon Stephens. As this name is not uncommon, I will provide some information to more uniquely identify myself. I am a Computer Science Ph.D. student at the University of Texas at Austin where I am a member of the [UToPiA](http://utopia.cs.utexas.edu/) group and advised by its fearless leader: [Isil Dillig](http://www.cs.utexas.edu/~isil/). 

Recent Publications
-----

<ul class="pub_list">
{% for post in site.publications limit:3 reversed %}
  {% capture pub %} {% include pub_list.html %} {% endcapture %} <li> {{ pub | strip_newlines }}
{% endfor %}
