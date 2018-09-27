---
id: 4
title: News!
date: 2014-03-11T19:18:39+00:00
author: Nick Gill
layout: page
---


The latest research news from the Department of Mathematics at the University of South Wales.

---

{% for post in site.posts %}

[{{ post.title }}]({{ post.url }})

Posted on {{ post.date | date: "%b %-d, %Y" }}

---

{% endfor %}

subscribe via [rss]({{ site.baseurl }}/feed.xml)

