---
layout: post
title:  "How to show post title first before blog title in search results?"
categories: bloggertricks
redirect_from:
 - /2015/01/show-blogger-post-title-name-first-in-search-results.html
permalink: blogger/tricks/show-post-title-first-before-blog-title/
tags: 
- blogger
- bloggertricks
description: Step by step guide to display your blog post name first then blog name in search results.
redirect_to:
  - https://blogger.goyllo.com/2015/10/show-post-title-first-before-blog-title.html
---

By default, blogger shows the blog title name first, then your post title name i.e. Blog name: post title. But if your blog name is too long, then Google surfers, don’t see your full post title name, because Google only shows the first 66 characters in search snippets, other characters will automatically ignore. So you have only two options, first one is, make your blog name or title shot, or use the below blogger technique to show your post title name first, then your blog name.

## Changing blog post title first before blog name. ##

First off go to template option.

Click on edit html option.

Find out below code.


    <title><data:blog.pageTitle/></title>

Replace above codes with below codes.

    <b:if cond='data:blog.pageType == &quot;item&quot;'>
    <title><data:blog.pageName/> | <data:blog.title/></title> <b:else/>
    <title><data:blog.pageTitle/></title>
    </b:if>

Click on save changes and visit your any post from browser, you will see your blog post title first, then your blog name. Don’t worry, you will see the same search result when Google index it.

### Useful guidelines for your old blog post. ###
Well, by following above steps, your new post will show something like this blog title: blog name, but what about your old blog post? It already index with blog name: blog title, so we should fix them. If your blog post link is internally linked to your other post, just like Wikipedia does in articles, then Google will update your blogger results in a few days, otherwise it will take some times to update automatically. But if you want quick result, then follow the simple steps.

#### Steps to update your old blog posts. ####

**Useful for many blog posts: It will take some time, may be a few days or months.**

I hope you already <a href="/webmaster/add-website-to-google-webmaster-tools/">submitted your blog/website to Google Webmaster Tools</a>, Now just fetch your blog URL to <a href="https://www.google.com/webmasters/tools/googlebot-fetch" rel="nofollow" target="_blank">Google webmaster fetch Tools</a> and submit it to index. In a few days your all old blog post will updated in search result.

**Useful for few blog posts: Instant result in fewer hours.**

You can submit your old specific blog post URL to <a href="https://www.google.com/webmasters/tools/submit-url" rel="nofollow" target="_blank">Google Webmaster tool</a> (GWT), this will update your old post in few hours. But you need to submit every URL to GWT, and it will take some times, hence do this only if you have only a few posts in your blogger dashboard, and want quick results in Google search.

I hope you will update your old post, now let’s continue.

## Does this useful in terms of SEO? ##

Well, this is all about how your post will look like in the search result, it doesn’t mean you ranked higher or you get a better position in search result. So I don't think its effect on [Blogger SEO](/blogger/seo/ "Blogger SEO"). Many of the Google official blog using blog name first, then post title, because they specified official words in blog name, and hence they get more click through rate (CTR) in search results, because most of people like to read the official, research and trusted content on the web. Hence, many of popular blog uses their brand name first. I hope you get my points, anyway, thanks for the reading.
