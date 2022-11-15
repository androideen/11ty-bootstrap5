---
title: Blog
hideTite: false
hideSidebar: true
layout: base.njk
templateEngineOverride: njk,md
eleventyNavigation:
  key: Blog

pagination:
    data: collections.posts
    size: 10
    alias: posts
    reverse: true
---

{% include "blog_posts.njk" %}
