---
layout: blogger
title:  "How To Add Google Analytics Code To Blogger?"
categories:
- bloggerbeginnertutorials
- blogger
permalink: blogger/beginner/add-google-analytics-code/
description: Step by step guide to add Google analytics tracking code in your blogger blog.
tags: 
- blogger
- googleanalytics
---

<div class="breadcrumb">
<span itemscope='itemscope' itemtype='http://data-vocabulary.org/Breadcrumb'><a href="/" itemprop="url"><span title="Goyllo" itemprop='title'>Goyllo</span></a></span>
<span itemscope='itemscope' itemtype='http://data-vocabulary.org/Breadcrumb'>&#187; <a href="/blogger/" itemprop="url"><span title="Blogger Tutorials" itemprop='title'>Blogger Tutorials</span></a></span>
<span itemscope='itemscope' itemtype='http://data-vocabulary.org/Breadcrumb'>&#187; <a href="/blogger/beginner/" itemprop="url"><span title="Beginner Tutorials" itemprop='title'>Beginner Tutorials</span></a></span>
</div>

In this post, I will show you, How to add/install google analytics tracking code in your blogger blog, so you can track everything. Well, first of refer this post about How to [add your website to Google analytics](/google/analytics/add-website-to-google-analytics/ "Add your website to Google Analytics"), and get your tracking ID or whole analytic codes.

Now, you have two things.

**1. Your short Google Analytics ID, for example UA-70093885-1**

**2. Full Tracking Codes**

Now, if you are using default blogger template, then you need to follow the first method, and if you are using another custom blogger template, that you have downloaded from another website, then you need to follow my second method. Well, sometimes, some blogger template developer, keep the blogger functionality same, so I think, you need to follow the first method, and if it is not working then, go for the second method.

## Method 1: Add Google Analytics ID, in your blogger setting. ##

Well, this is a very simple method, you can directly connect your blogger blog to Google analytics.

First off go to setting « other option.

Now, scroll down, and you will see Google analytic option, just like this.

<img class="img-responsive" alt="Add Google Analytics ID to Blogger Blog" src="{{ site.imgurl }}/Add-Google-Analytics-ID-to-Blogger-Blog.png" title="Add Google Analytics ID to Blogger Blog"/>

Now enter your Analytics web property ID (for example UA-70093885-1), and save settings.

## Check analytics code, is implemented successfully or not? ##

Now, it’s time to check, you have implemented google analytics code in the right way or not, so first of open your blog URL, and right click on anywhere, and select view page source from browser option. Now press CTRL+F to find codes, in your template. So just search your analytic ID, like this.

<img class="img-responsive" alt="Checkout Google Analytics Code in Blogger" src="{{ site.imgurl }}/checkout-google-analytics-code-in-blogger.png" title="Checkout Google Analytics Code in Blogger"/>

So if you found your analytic ID it means you have implemented code successfully. And if you did not find it, it means, your template code does not support that widget directly, we need to implement by using our second method.

## Method 2: Add Google Analytics Codes, in your blogger template. ##

First off go to template « Edit HTML.

Now, the small question is, **where to paste Google analytics code in blogger?**, well, if you already read my  [previous post](/google/analytics/add-website-to-google-analytics/#where-to-put-google-analytics-code-in-my-website "Where to put Google Analytics Code in my website?"), then you will see, I have mentioned, you can add analytics code anywhere. By Default blogger template, add analytics code in heading section, but it is not good practice to add analytics code in heading section, so most of developer suggests to paste the analytics code before  `</body>` tag.

<img class="img-responsive" alt="Add Google Analytics Code To Blogger Template" src="{{ site.imgurl }}/Add-Google-Analytics-Code-To-Blogger-Template.png" title="Add Google Analytics Code To Blogger Template"/>

Now, find `</body>` tag, , in your template, and paste your analytics codes just above it, refer below screen shot for better understanding.

Now, just check out again to make sure, you have implemented code successfully or not. Feel free to comment, if you have any doubt.