---
layout: page
title: Index
permalink: /
excerpt_separator: <!--end_of_excerpt-->
---



# My thoughts on software maintainability

{% for post in site.posts %}

### [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}

{% endfor %}
