---
layout: post
title:  "Blogger XML Sitemap : Hidden Features"
categories: bloggerseo
redirect_from:
 - /google/blogger/seo/xml-sitemap/
permalink: blogger/seo/xml-sitemap/
tags: 
- blogger
- seo
---

A blogger creates a sitemap automatically whenever you published any content on your blog post or page. In other words, you cannot change your sitemap, or you cannot add or host blogger sitemap, there is no any customization facility given by blogger.

This one is your post sitemap 

    www.example.blogspot.com/sitemap.xml

This one is your page sitemap

    www.example.blogspot.com/sitemap-pages.xml

Similarly you can also find your own sitemap for post and pages, just by changing example name to yours blog name.

You should use this sitemap whenever you need to implement your blog sitemap somewhere like Google webmaster Tool or Bing Webmaster Tools or any other third party site where sitemap is needed to submit.

Another thing you should note that, the blogger sitemap is changed automatically according to your number of posts.

Look out this guy <a href="http://blogging.nitecruzr.net/sitemap.xml" rel="nofollow" target="_blank"> sitemap</a>

There are multiple sitemap into main sitemap.

    /sitemap.xml?page=1
    /sitemap.xml?page=2
    /sitemap.xml?page=3


So initially when your total number of posts is less than 500, then your all post link goes to main sitemap i.e. www.example.blogspot.com/sitemap.xml but when you post your 501 posts, then, your main sitemap will change i.e. your first 1-500 post will be listed out in sitemap.xml?page=1, and another 500-1000 listed out in sitemap.xml?page=2 and so on….. And all these sitemap pages are pointing to our main sitemap.

So whenever you need to add a sitemap somewhere like Google webmaster tool, then you just need to submit your main sitemap (i.e. www.example.blogspot.com/sitemap.xml), not all the sitemap. Also, you should submit your sitemap for page (i.e. www.example.blogspot.com/sitemap-pages.xml), if you think it is important to submit.

Another thing is that there is a **minor bug in blogger sitemap**, when you reach your 2501 posts, then Blogger will create the sitemap page www.example.blogspot.com/sitemap?page=6 automatically, but it is not listed out in your main sitemap. So once you reach your post to 2501, then you need to submit these sitemap into Google Webmaster Tools.
 

    www.example.blogspot.com/sitemap.xml
    www.example.blogspot.com/sitemap.xml?page=6

I hope you get my point, you can even submit your atom feed as a sitemap for blogger blog.

This post is only for information about the hidden blogger sitemap, you did not worry about it. Actually, there is no any official documentation on that, hence I posted in my blog, so you know about it. Anyway, thanks for the reading. Have a good day.

