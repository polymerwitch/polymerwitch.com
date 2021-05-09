---
layout: index.liquid
---
# polymerwitch 👩‍💻
<a rel="me" href="https://social.polymerwitch.com/@polymerwitch">Mastodon</a>
|
<a href="https://polymerwitch.bandcamp.com">Bandcamp</a>
|
<a href="https://github.com/polymerwitch">Git</a>
|
<a href="about.html">About</a>

___


## Posts

{% for post in collections.posts.pages %}
### [{{post.title}}]({{ post.permalink }})
{{ post.content }}

<div class="tilde">~~~</div>

{% endfor %}
