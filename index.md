---
title: Home
---

# My Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

# My Projects

### [Counter](https://github.com/Shrimp-coder17/Counter.git)