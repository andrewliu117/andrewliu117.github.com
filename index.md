---
layout: page
title: The first page
tagline: Have a good day, Luke!
---
{% include JB/setup %}

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)
    
## Blogs
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Links
<ul class="simple">
	<li> <a href="html/mathequations.html">How to display math equations in web</a></li>
	<li> <a href="html/githubblog.html">How to blog on github</a></li>
	<li> <a href="html/linux.html">Linux related stuff</a></li>
</ul>
