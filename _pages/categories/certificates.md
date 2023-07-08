---
title: "자격증"
layout: archive
permalink: categories/certificates
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.certificates %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}