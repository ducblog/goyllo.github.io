---
layout: jekyll
title:  "Why I chose Jekyll over WordPress"
categories:
- jekyllbeginner
- jekyll
redirect_from:
 - /jekyll/personal/jekylll-over-wordpress/
 - /jekyll/jekylll-over-wordpress/
 - /jekyll/jekyll-vs-wordpress/
permalink: jekyll/beginner/jekyll-vs-wordpress/
tags: 
- personal
- jekyll
description: Here, is my personal review about Jekyll, and Why I like jekyll over WordPress.
---

<div class="breadcrumb">
<span itemscope='itemscope' itemtype='http://data-vocabulary.org/Breadcrumb'><a href="/" itemprop="url"><span title="Goyllo" itemprop='title'>Goyllo</span></a></span>
<span itemscope='itemscope' itemtype='http://data-vocabulary.org/Breadcrumb'>&#187; <a href="/jekyll/" itemprop="url"><span title="Jekyll Tutorials" itemprop='title'>Jekyll Tutorials</span></a></span>
<span itemscope='itemscope' itemtype='http://data-vocabulary.org/Breadcrumb'>&#187; <a href="/jekyll/beginner/" itemprop="url"><span title="Beginner Tutorials" itemprop='title'>Beginner Tutorials</span></a></span>
</div>

Well, I start blogging, when I was in the first year of Computer Engineering degree (2011), I started my blogging journey from <a href="/blogger/">Google blogger</a>, and actually it's simple and powerful blogging platform ever, I am not a professional blogger, so I just post some tricks and tips about computer. After two years, I was learning many things in the internet. Many of professional blogger choose WordPress over blogger, because of flexibility, control and absolutely plugins that make life easy for anyone, also WordPress cover more than 20% of the web according to w3tech. So I just try out WordPress with my friend hosting site. I did not face any problem while setup, because I already learn a lot of about WordPress in my local host. I just install some plugins like w3total cache, Jetpack, SEO by Yoast. Well everything is working fine. But after a few days, the SEO by Yoast plugin got vulnerable, also I use <a href="/internet/get-news-in-your-email/"> Google alert </a>for "Zero Day Exploit" Where I got most of news about Microsoft and WordPress Vulnerability. Then I miss Google blogger platform, because it is hosted on Google cloud, so it's more secure than any.

WordPress takes more time to serve web pages over browser compare to static web pages. So I realize let's build my own website. But it's very time consuming process, also you cannot categorize your post easily. Lots of work I should do to generate static web pages with easy navigation. Then I just found <a href="http://jekyllrb.com/" rel="nofollow">Jekyll</a>. Jekyll is not exactly blogging software, but it's behaving what you want exactly. On the first try, I failed to install Jekyll properly on Windows, and may be you will also fail in first time because of Microsoft OS and its dependency. But after some try I was success to install Jekyll on Windows. I never know about the Ruby, Liquid Templates, YML and gems. Also, I never familiar with Git. So it's taken some days to learn. After learning some few basics, I just say Jekyll is simply awesome. Here is why?

## Jekyll vs WordPress ##
Let’s see, in which cases Jekyll is a winner.

## Speed ##
The speed of any static site generator is can’t beat by any CMS. Because static site does not wait for process like executing query on database. If you are a WordPress developer, then you will note, every time, whenever any page is loaded, then the query is executed on the database server and hence it’s taken some millisecond (ms) to process those queries. So, the modern static site generator like Jekyll, Hugo, Hexo is too fast compared to any CMS.

## Security ##
No SQL query, No database. It's simply secure your website from SQLI (SQL Injection) leet or 1337 or Master, because there is nothing to **inject**.

## Custom permalink for a specific post ##
Jekyll support all the permalink features that WordPress gives you. Also you can setup your own custom permalink in any post. For example

    Permalink: test1/test2/test3/custom-title-of-post/ 

Output will be look like this.

    www.example.com/test1/test2/test3/custom-title-of-post/

First, I was using categories into my permalink but after finding this solution, I can use any of permalink for my post. Even I can set two different permalinks for two different posts. For example


    Permalink: test1/test2/test3/custom-title-of-post // post 1 permalink
    Permalink: 2015/06/custom-title-of-post           // post 2 permalink


It's not awesome? Where In WordPress, Once you choose any permalink format, it's applied to all posts, but in Jekyll you can customize it.

## Custom layout for a specific post ##
I am not a master in WordPress, so I don't know really much more about the post layout in WordPress, But Does WordPress supports different layouts for different post? Absolutely not. It's painful for WordPress developers, where in Jekyll you can. For example.

You have posted many things in your blog, and places some ads or newsletter or something else in your site sidebar, but not all the peoples are interested. For example, if you post articles about blogging then blogger will click on it and you get maximum results from blogger visitors, because it is relevant to him/her. But what about the other peoples? Your sidebar is simply displayed in all your posts, and it is fixed. But what happens if you can change the sidebar layout according to your post. For example, in blogger post you can display blogger layout and for social media tips you can display other layout. It's not awesome? Not only sidebar but you can create your own layout for any post. You just need to specify which layout you want to use for your post in single line, like this.

    Layout: Post              //I used this layout for my posts
	Layout: Page              //I used this layout for my pages like about 
	Layout: Directory         //I used this layout for directory like /google/
    Layout: NoAds             //I used this layout if I don't want to display ads
    Layout: Blogger           //I used this layout for blogger post only 

## Custom Directory ##
Well, this is what I loved about the Jekyll, as I said above I can create custom permalink as per my choice, but you can even create your own directory and you can put anything you like. For example I just created <a href="/google/"> google/ </a> directory, where I display various Google products in simple rectangular box. But in <a href="/blogger/beginner/"> /blogger/beginner/</a>, I display blogger beginner tutorials with title and description, by using the loop and categories option. In short I can say, the flexibility of Jekyll is can't beat by WordPress.

## Powerful Backup ##
There are two different scenarios in the backup process. In WordPress, user write the post and publish it. Most of all user backup its data weekly, and some of pay for backup to host provider. Where in Jekyll, you can test your post in local host, and most of them, including me test out the post in local host first, and then deploy it to server. So you have already backup of your all posts in local machine. So whenever you need to change the host server, just upload all the data to new host. No other cost is required.

## Developer Team ##
WordPress developed by master of master. They assign code is poetry. But there are many of plugin developers, they charges for the plugin, but in Jekyll, all the developers are free to help. Even I was finding all the necessary codes from stack overflow and github, and then I am changing it according to my need.

## Github-Pages Support ##
Well, <a href="https://pages.github.com" rel="nofollow">Github pages</a> provide you free hosting for Jekyll. With Github pages, your site use Github CDN (Content Delivery Network). It will accelerate your website access and delivery web pages from different location. Currently I am also using Github pages, to host this website, but later I am thinking to use the Amazon S3 cloud.

So, this is just a small comparison between **Jekyll vs Wordpress**, If you know some few basic of HTML then I highly recommended to give it try to static site generator like Jekyll, Hugo or any others.
