---
title: "Codahedron"
layout: base-page
---



<div class="main-content window win-big" markdown="1">

# Codahedron

We are Codahedron, a company run by two data science students in Gothenburg, Sweden. 

We firmly believe in the importance of a strong open source community, and whereas producing open source software is not our goal, we aim to share what we can of our own work, such that others can use it to create things that might not have been created otherwise. 

In addition, we are very aware of the importance of user privacy in the all-connected world of today. With that in mind, and our backgrounds in data science, we aim to utilize modern data collection and analysis to improve the user experience, while infringing as little as possible on their privacy.

Our first big project is **Network: Override**, a cyberpunk-inspired game about hacking, which is planned to be released at some point in the future.

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


<div class="main-content window" markdown="1">

#### About Us

Coming soon.

</div>
