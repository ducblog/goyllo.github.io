---
layout: post
title:  "How to remove powered by blogger attribution?"
categories: bloggerwidget
redirect_from:
 - /google/blogger/widget/remover-powered-by-blogger-attribution/
permalink: blogger/widget/remover-powered-by-blogger-attribution/
tags: 
- blogger
description: Step by step guide to remove powered by blogger attribution from your blog.
---

In this tutorial, I will tell you how to remove “powered by blogger” attribution widget/gadget that appear in the blogger footer. As per my suggestion, you should not remove the “powered by blogger” attribution, keep the credit link as it is, but if you really want to remove it, then go ahead, don’t worry your blogger blog will not remove by Google.

## Steps to remove Powered by blogger attribution.##

- First off go to blogger template option, and click on the Edit HTML option. Look out below screenshot for better understanding.

<img class="img-responsive" alt="Blogger Template - Edit HTML" src="/images/blogger-template-edit-html.png" title="Blogger Template - Edit HTML" /><br />

- Now Click to Jump to Widget and select Attribution widget like this,

<img class="img-responsive" alt="Powered by blogger attribution widget" src="/images/blogger-attribution-widget.png" title="Powered by blogger attribution widget"/><br />

*Well, if you did not find it, then you can use the CTRL + F to find “Attribution” keyword.*

- Now you will see these lines of codes.<br/>

    `<b:widget id='Attribution1' locked='true' title='' type='Attribution'>....</b:widget>`

- Now changed the locked value from true to false, like this,<br/>
   `<b:widget id='Attribution1' locked='false' title='' type='Attribution'>....</b:widget>`

- Don’t change any other value, and click on save the template.

- Now go to the layout option, and click on Attribution widget, and now you can see the removal option. So just click on it, and save your settings. I hope you will successfully remove the powered by blogger attribution widget from your blog.

<img class="img-responsive" alt="Remove powered by blogger attribution widget" src="/images/remove-powered-by-blogger-attribution-widget.png" title="Remove powered by blogger attribution widget" /><br />


#### Why “Powered by blogger” appear again after removing it? ####

Well, we have no more control, in our blog, so the standard code will automatically add in your blogger blog anytime.

**Solution**: Just delete whole attribution widget codes, and click on save the template. Most times, that has worked for me on any blogger template.
