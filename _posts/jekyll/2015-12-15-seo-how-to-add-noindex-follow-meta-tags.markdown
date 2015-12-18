---
layout: post
title:  "How to Add Noindex Meta Tags in Jekyll Pages?"
categories:
- jekyllseo
- jekyll
permalink: jekyll/seo/noindex-follow-meta-tags/
tags: 
- jekyll
- personal
description: Learn How to add noindex, follow Meta tags in specific Jekyll pages to prevent Google Panda penalties.
---

<div class="breadcrumb">
<span itemscope='itemscope' itemtype='http://data-vocabulary.org/Breadcrumb'><a href="/" itemprop="url"><span title="Goyllo" itemprop='title'>Goyllo</span></a></span>
<span itemscope='itemscope' itemtype='http://data-vocabulary.org/Breadcrumb'>&#187; <a href="/jekyll/" itemprop="url"><span title="Jekyll Tutorials" itemprop='title'>Jekyll Tutorials</span></a></span>
<span itemscope='itemscope' itemtype='http://data-vocabulary.org/Breadcrumb'>&#187; <a href="/jekyll/seo/" itemprop="url"><span title="Jekyll SEO" itemprop='title'>Jekyll SEO</span></a></span>
</div>

Here I will guide you how to add noindex and follow Meta tags in specific Jekyll pages.

Here is what Google said about this Meta tags.

    <meta name="robots" content="noindex, follow">      .......(1)

This X-robots, tell Google to don’t index this page, but follow my other links on that page, i.e. that page will not allow to index on Google search result, but links on that page are allowed to crawl i.e. PageRank will flow from one link to another.

## Why should you add noindex Meta tags to specific pages? ##
If you look out on mine directory or folder, like /Jekyll/, /blogger/, and /Google/ then view my page source, and you will see above Meta tags (equation 1) in the head section. So that pages will not be indexed by Google. But the question is why we should not index those pages on Google search.

So, the reason is Google Panda Penalty. In simple words, Google wants to index only high-quality content, but such a directory, categories and tags are not qualified for high-quality pages, and hence I decide not to index them on search engine result. So I will not get any Google penalty on future. You can do the same, in your Jekyll blog, so the conclusion is **Use noindex Meta tags in categories, tags or directory**.

## Steps to add noindex, follow Meta tags in Jekyll. ##

First, add this line in your front matter, `metatags: noindex, follow` like this.

    ---
    layout: page
    title: Google
    permalink: /google/
    metatags: noindex, follow
    ---

Now, go to includes folder, and open your head.html file.

Now, add this line anywhere between `<head>` to `</head>` tags.

    {% raw %}{% if page.metatags %} <meta name="robots" content="{{page.metatags}}">{% endif %}{% endraw %}

Here, we check if the specific page contains Meta tags or not, if it contains, then above line will be executed. Otherwise, it will ignore by Jekyll and that Meta tags will not add in your heading section. For example, if we did not add that Meta tags in our blog post, then it will be not added in our head section, and our blog post will be an index on Google search result. Hope it's more clear now.

You can even use other [Meta tags](https://support.google.com/webmasters/answer/79812?hl=en "Meta Tags That Google Understand") like noodp, nosnippet, noarchive etc., in your front matter.