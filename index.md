---
title: Home
---
<div style = "text-align:center;">
	<img src = "assets/images/me.JPG" alt="Me">
</div>

# My Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

# My Projects

### [Counter](https://github.com/Shrimp-coder17/Counter.git)
### [GameState](https://github.com/Zen1914/GameState.git)