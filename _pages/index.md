---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome to donguridong
---

## Who is she?

{% include components/intro.md %}



> MS.'s Course
>
> interested in computer vision & Deep learning



------

## Why she made blog?

To study hard .... new department !



<hr />

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


