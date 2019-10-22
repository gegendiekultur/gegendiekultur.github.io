---
layout: blog
title: Gegen die Kultur - Blog
---
<div class="png2" id="aktuelles">
        <div class="ptext">
                <span class="bd trans">
Aktuelles
                </span>
        </div>
</div>
<div class="textcard">
{% for post in site.posts %}
<h2>{{ post.title }}</h2>
{{ post.excerpt }}
<br />
<a href="{{ post.url }}">weiterlesen...</a>
<hr>
{% endfor %}
</div>
