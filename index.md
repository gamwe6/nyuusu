---
layout: default
---
<ul>
   {% for post in site.posts %}
      <li><a href="{{ post.url | prepend: site.baseurl }}" title="{{ post.title }}">{{ post.title }}</a></li>
   {% endfor %}
</ul>
