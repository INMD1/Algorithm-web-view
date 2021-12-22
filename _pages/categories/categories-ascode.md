---
title: "Posts by category"
layout: archive
permalink: categories/ascode/
author_profile: true
sidebar_main: true
---

{% assign posts = site.categories.ascode %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}