---
title: "모든 게시글"
layout: archive
permalink: /categories
author_profile: true
sidebar_main: true
---

## SPRING
{% assign posts = site.categories.SpringBase %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}

## ALGORITHM
{% assign posts = site.categories.AlgoBoj %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}

{% assign posts = site.categories.AlgoBase %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}