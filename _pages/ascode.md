---
title: "Posts by category"
layout: archive
permalink: ascode/
author_profile: true
---

{% assign posts = site.ascode %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}