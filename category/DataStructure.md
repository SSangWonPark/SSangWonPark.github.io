---
layout: archive
permalink: /category/DataStructure/
title: DataStructure
sidebar_main: true
---

{% assign posts = site.categories["DataStructure"] | default: site.categories["datastructure"] %}
{% for post in posts %}
{% include archive-single.html type=page.entries_layout %}
{% endfor %}
