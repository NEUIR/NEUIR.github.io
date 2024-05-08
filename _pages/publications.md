---
layout: splash
classes: wide
title: Publications
permalink: /publications/
header:
  overlay_filter: linear-gradient(rgba(0, 0, 0, 0.5), rgba(223, 81, 39, 0.5))
  overlay_image: "/assets/school.jpg"
  caption: "[**NEUIR**](/) of [**NorthEastern University**](https://neu.edu.cn)"
---
## Conference
{% include scholar/_includes/publications venue_search=" " link=true %}

## Journal
{% assign journal_list = site.publications.journals | join: ";" %}
{% include scholar/_includes/publications venue=journal_list link=true %}
