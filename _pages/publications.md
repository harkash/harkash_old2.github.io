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

<br>
<b> [On the Role of Features in Human Activity Recognition](https://harkash.github.io/publication/on-the-role-of-features-in-har)</b><br>
<i> International Symposium on Wearable Computers </i> <b> ISWC 2019 </b> 


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
