---
layout: post
title:  "How to get website IP address easily with command line tools?"
categories: internet
comments: true
permalink: internet/know-website-ip/
tags: 
- internet
- website
---

Every website is hosted on the server machine, and using DNS to remember website name easily, so behind DNS, there is the original IP address of the machine or content delivery network (CDN) server IP address. If some of the website using a third party CDN, then you can’t get the original IP of a website, but most of the webmaster only using a CDN to serve files like JavaScript, CSS, Icons, Images etc in order to increase website loading speed. And other content is delivered direct from the original source, so you will get the real IP address in most of the scenario.

## Get Website IP address Using CMD ##

First off run CMD as administrator.

   <img alt="CMD run as administrator" src="/images/cmd-run-as-administrator.png" height="300" title="CMD run as administrator" width="240" />

Now type this “ping www.google.com” (without quotas), so you will get the google IP address, similarly you can find any of website IP addresses easily, just by replacing www.google.com domain names to another domain like “ping www.facebook.com"

 <img alt="ping website domain name" src="/images/ping-domain-website-name.png" height="241" title="ping website domain name" width="500" />

To verify it’s a original IP address, just enter the IP address in browser tab and hit enter, if you get the website homepage, then IP address of that website is right, otherwise the website owner using third party CDN (for example <a href="https://www.cloudflare.com/" rel="nofollow" target="_blank">cloudflare</a>), to hide it’s original server to prevent DOS attack.

**Note**:- In this tutorial, I was demonstrate with google URL, but they are changing it’s server address many times, so may be above IP will not same that you find out with CMD tools. Also note that, some of website owners, does not allow to access their website directly to the IP address (for example superuser.com). I hope you understand it. You can also use other command line tools/terminal as per your operating system (Mac or Linux). Thanks for reading. Have a good day.