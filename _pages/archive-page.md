---
layout: archive
title: "Page Archive"
permalink: /page-archive/
author_profile: false
excerpt: "All the pages of this site"
---

{% for post in site.pages %}
{% unless post.hidden %}
{% include archive-single.html %}
{% endunless %}
{% endfor %}
