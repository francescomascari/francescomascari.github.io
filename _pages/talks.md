---
layout: archive
title: "Talks, Posters, and Conferences"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

# Talks

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

# Posters

{% for post in site.posters reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
