---
title: "Posts by category"
layout: tags
permalink: /ascode/
author_profile: true
---

{% assign posts = site.categories %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}