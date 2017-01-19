---
layout: page
permalink: /blog/
---

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>  
      <div class="info">by {{ page.author }} on {{ page.date | date_to_long_string }}</div>

      <div class="entry">
        {{ post.excerpt | remove: '<p>' | remove: '</p>' }}... <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
      </div>


    </article>
  {% endfor %}
</div>