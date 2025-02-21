---
layout: archive
title: "Talks, Posters, and Conferences"
permalink: /talks/
author_profile: true
---

{% include base_path %}


# Talks

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

---

# Posters

{% for post in site.posters reversed %}
  {% include archive-single-poster.html %}
{% endfor %}
