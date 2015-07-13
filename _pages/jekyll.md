---
layout: page
title: Jekyll Tutorials
permalink: /jekyll/
redirect_from:
 - /jekyll/personal/
---
<ul class="post-list">
	{% for post in site.categories.jekyll reversed %}
      <li>	
        <h2>
         <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>   
        </h2>
	<p><i>{{post.excerpt | truncatewords: 30 }}</i></p>
      </li>
    {% endfor %}
  </ul>