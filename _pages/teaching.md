---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

Please click [here](https://rileyleague.github.io/files/League_Riley_Teaching_Statement.pdf) for my research statement.

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
