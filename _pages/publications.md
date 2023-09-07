---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

* <span style="font-size:11pt;">**Exploring the Link Between Innovation and Firm Growth in Chilean Firms**, with Caterina Santi</span>
   - <span style="font-size:11pt;">*Small Business Economics* (2017), 49: 445</span>
   - <span style="font-size:11pt;">[[Paper](https://link.springer.com/article/10.1007/s11187-016-9836-4)] [[WP](http://www.lem.sssup.it/WPLem/files/2016-09.pdf)]</span>
