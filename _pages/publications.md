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


International Conferences
------
<hr style="border:1px solid gray"> 
{% for post in site.publications reversed %}
{% if post.tags  contains "conf" %}
  {% include archive-single.html %}
{% endif %}
{% endfor %}


Reviewer
------
<hr style="border:1px solid gray"> 
* [ICANN'21](https://e-nns.org/icann2021/): The 30th International Conference on Artificial Neural Networks, 2021. 
