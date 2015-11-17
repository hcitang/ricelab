---
title: Publications
subtitle: Fabulous bathroom reading
featured: /assets/images/banner.jpg
layout: default-paperlist
permalink: "/papers/"

---
{% assign latestYear = site.time | date: '%Y' %}
{% for y in (2004..latestYear) reversed %}
<h1><a name="{{ y }}"></a>{{ y }}</h1>
{% bibliography --query @*[year={{ y }}] %}
{% endfor %}