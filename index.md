---
title: "Codahedron"
layout: base-page
---



<div class="main-content window win-big" markdown="1">

# Codahedron

We are Codahedron, a small company based in Gothenburg, Sweden. We develop games, software and provide consultation. Whereas not all software we develop is open source, the open source ideals are very important to us, since it provides positively to both collaboration and competition. Therefore our aim is to produce software in an ethical and as-open-as-possible manner, while maintaining economical viability.

Our first big project is **Network Override**, that is planned to be released at some point in the future. More to come on this later.

</div>

<div class="blog-list window win-wide-2">
   <h2> Most Recent Posts </h2>
   {% for post in site.posts limit:3 %}
      <div>
         <h3>
            <a href="{{ post.url | relative_url }}"> {{ post.title }} </a>
         </h3>
         <p style="margin: 0;"> {{ post.date | date_to_long_string}}{% if post.author %}, {{ post.author }}{% endif %} </p>
      </div>
   {% endfor %}
</div>

<div class="main-content window win-wide-2" markdown="1">
<img src="/assets/images/new-zealand-lake-mountains-road-4.jpg">

This is a lake in New Zealand.
</div>

<div class="main-content window win-wide-2" markdown="1">

#### About Us

Coming soon.

</div>
