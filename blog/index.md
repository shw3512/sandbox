---
permalink: /blog/
---
{% for post in sites.posts %}
- {{ post.date }} : [{{ post.title }}]({{ post.url}})
    > {{ post.excerpt }}
{% endfor %}