---
title: Blog
---
# Blog Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

Jekyll Tip: Posts are auto-sorted by date in filename.