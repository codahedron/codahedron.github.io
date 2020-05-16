---
title: Blog
author_profile: true
permalink: /blog/
---

{% for post in site.posts%}
  {% include blog-preview.html %}
{% endfor %}
