---
layout: page
title: Thoughts on software
permalink: /
excerpt_separator: <!--end_of_excerpt-->
---


# My thoughts on software maintainability

{% for post in site.posts %}

### [{{ post.title }}]({{ post.url }}) ({{ post.date }})
{{ post.excerpt }}

{% endfor %}
