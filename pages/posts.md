---
title: Posts
permalink: /blog/
author: all
layout: default
---

{% for post in site.posts %}
*  [{{post.title}}]({{post.url }})
{% endfor %}
