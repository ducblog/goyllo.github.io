---
layout: page
title: SEO Tutorials for Beginners
redirect_from:
 - /webmaster/seo/beginner/
permalink: /seo/beginner/
---
<ul class="post-list">
	{% for post in site.categories.beginnerseo reversed %}
      <li>	
        <h2>
         <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>   
        </h2>
		<p><i>{{post.excerpt | truncatewords: 30 }}</i></p>
      </li>
    {% endfor %}
  </ul>
