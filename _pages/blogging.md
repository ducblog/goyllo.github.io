---
layout: page
title: Blogging for Beginners
permalink: /blogging/
---
<ul class="post-list">
	{% for post in site.categories.blogging reversed %}
      <li>	
        <h2>
         <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>   
        </h2>
	<p><i>{{post.excerpt | truncatewords: 30 }}</i></p>
      </li>
    {% endfor %}
</ul>