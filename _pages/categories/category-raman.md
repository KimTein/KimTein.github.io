---
title: "Raman Spectroscopy"
layout: archive
permalink: categories/raman
author_profile: true
sidebar_main: true

excerpt: "Talking about Raman Spectroscopy"
header:
  overlay_image: /assets/images/posts/raman/raman-header1.jpg
  overlay_filter: 0.4 # same as adding an opacity of 0.5 to a black background
  #linear-gradient(rgba(255, 255, 255, 1.0), rgba(255, 255, 255, 0.5))
  #caption: "Photo credit: [**show name**](url)"
  actions:
    - label: "Lab. AMS"
      url: "https://www.inu.ac.kr/user/indexMain.do?siteId=physics_eng"
      
---

{% assign posts = site.categories.raman %}
{% for post in posts %}{% include archive-single2.html type=page.entries_layout %} {% endfor %}