---
title: Dave Mackintosh's Blog
tags:
  - page
keywords:
  - serverless
  - architect
  - platform
  - native
  - engineer
  - mentor
  - manager
description: With 20 years of software development expertise and a successful 10-year solo business. Explore my track record of working with renowned clients and delivering stable, high-performant code with a people-first approach
---

# Blog

{% for post in content.blog %}
{% render "post-card", post: post %}
{% endfor %}
