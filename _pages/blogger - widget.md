---
layout: page
title: Blogger Widgets
redirect_from:
 - /google/blogger/widget/
permalink: /blogger/widget/
---
<ul class="post-list">
	{% for post in site.categories.bloggerwidget reversed %}
      <li>	
        <h2>
         <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>   
        </h2>
	<p><i>{{post.excerpt | truncatewords: 30 }}</i></p>
      </li>
    {% endfor %}
  </ul>