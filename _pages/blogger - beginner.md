---
layout: page
title: Blogger - Beginner Tutorials
redirect_from:
 - /blogger/beginner-tutorials/
 - /google/blogger/beginner-tutorials/
permalink: /blogger/beginner/
---
  <div class="posts">
	{% for post in site.categories.bloggerbeginnertutorials reversed %}
	<div class="post">
     <a href="{{ post.url | prepend: site.baseurl }}" class="post-link"><h3 class="h2 post-title">{{ post.title }}</h3></a>
	  <p class="post-summary">
          {% if post.summary %}
            {{ post.summary }}
          {% else %}
            {{ post.excerpt  | truncatewords: 25}}
          {% endif %}
        </p>
		</div>
    {% endfor %}
  </div>