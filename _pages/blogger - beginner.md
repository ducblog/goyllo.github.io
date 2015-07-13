---
layout: page
title: Blogger - Beginner Tutorials
redirect_from:
 - /blogger/beginner-tutorials/
 - /google/blogger/beginner-tutorials/
permalink: /blogger/beginner/
---
<ul class="post-list">
	{% for post in site.categories.bloggerbeginnertutorials reversed %}
      <li>	
        <h2>
         <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>   
        </h2>
		<p><i>{{post.excerpt | truncatewords: 30 }}</i></p>
      </li>
    {% endfor %}
  </ul>