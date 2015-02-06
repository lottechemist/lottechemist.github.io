---
layout: page
title: Archive
---

## Archive

{% for post in site.posts %}
<span class="light-grey-text">{{ post.date | date_to_string }} </span> [ {{ post.title }} ]({{ post.url }})
{% endfor %}