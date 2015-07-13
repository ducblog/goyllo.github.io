---
layout: page
title: Blogger Widgets
redirect_from:
 - /google/blogger/widget/
permalink: /blogger/widget/
---  
  <div class="posts">
	{% for post in site.categories.bloggerwidget reversed %}
	<div class="post">
     <a href="{{ post.url | prepend: site.baseurl }}" class="post-link"><h3 class="h2 post-title">{{ post.title }}</h3></a>
	  <p class="post-summary">
          {% if post.summary %}
            {{ post.summary }}
          {% else %}
            {{ post.excerpt  | truncatewords: 30}}
          {% endif %}
        </p>
		</div>
    {% endfor %}
  </div>