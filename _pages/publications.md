---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Research
------
Real-world data usually contain mixed data types as numerical, categorical, sequence, etc... To extract valuable information from these data one can use for instance machine learning methods. However, in the litterature there exists mostly methods for handling one data type. Therefore one should convert the other data types, for instance converting all non-numeric data to numeric. This convertion can lead to loss of information.

In my thesis I am working on the development of clustering methods that can efficiently handle numerical and categorical data at the same time. In particular, we are interested in developing these methods in the fuzzy and belief functions frameworks that can respectively express the fuzziness and incertitude of assigning objects to the clusters.

Peer-reviewed publications
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
