---
layout: page
title: Archive
---

<p class="message">
  "Previous posts"
</p>

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}