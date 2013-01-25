---
layout: page
title: Welcome to Open World
tagline: Supporting tagline
---
{% include JB/setup %}

I'm [Arpan Chavda](http://arpan-chavda.github.com),
 
 21 years old Indian developer,opensource enthusiast,linuxer,
computer science student and technology explorer.


##My Blog posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Working on /dev
I'm currently working on developement of custom GNU/Linux distributions.Look at [here](https://github.com/codejar-lab).



