---
layout: index
title: Home
permalink: /
---

# Welcome!

The Bennett Hydrology Lab in the [Department of Hydrology and
Atmospheric Sciences](https://has.arizona.edu/) at the University of Arizona
uses computational methods to understand and predict the hydrologic cycle. We use
and develop a variety of computational methods, including numerical modeling,
data analysis, and machine learning. We are particularly interested in developing
the new ways to model and analyze the terrestrial hydrologic cycle on regional to
global scales. Our interests include a variety of processes including surface water
hydrology, interactions between hydrology and vegetation, and the effects of climate
change on hydrologic processes. Our lab also develops open-source software for hydrologic
modeling and data analysis.

# Latest News
{% for post in site.categories['news'] %}
  - [{{ post.title }}]({{ post.url }})
{% endfor %}