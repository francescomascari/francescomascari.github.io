---
permalink: /talks/
layout: archive
title: "Talks, Posters, and Conferences"
excerpt: "Talks, Posters, and Conferences"
author_profile: true
---

{% include base_path %}
---

# Talks

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}

---
# Posters

{% for post in site.posters reversed %}
  {% include archive-single.html %}
{% endfor %}

---
# [Other Conferences, Workshops, and Schools](https://francescomascari.github.io/talks/talks_other)
