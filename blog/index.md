---
title: Blog
author_profile: true
permalink: /blog/
---

<div class="blog-list win-wide-3">
   {% for post in site.posts%}
      <div class="window win-wide-2">
         {% include blog-preview.html %}
      </div>
   {% endfor %}
</div>
