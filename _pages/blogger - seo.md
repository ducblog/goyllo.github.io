---
layout: page
title: Blogger SEO
redirect_from:
 - /blogger/seo-tutorials/
 - /google/blogger/seo/
permalink: /blogger/seo/
---
  <div class="posts">
	{% for post in site.categories.bloggerseo reversed %}
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