---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Index
---

See [About me](/about)

I have posted a small amount of posts
{% for post in site.posts %}
## [{{post.title}}]({{post.url}})
{% endfor %}
