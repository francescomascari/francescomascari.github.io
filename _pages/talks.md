---
permalink: /talks/
layout: archive
title: "Talks, Posters, and Conferences"
excerpt: "Talks, Posters, and Conferences"
author_profile: true
---

{% include base_path %}

# Posters

{% for post in site.posters reversed %}
  {% include archive-single-poster.html %}
{% endfor %}
