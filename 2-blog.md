---
layout: page
title: Blog
tooltip: BA tips and techniques
permalink: /blog/
---

<ul class="post-list">
{% for post in site.posts %}
  <li>
    <!-- <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span> -->

    <h2 style = "clear: both">
      <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a> 
    </h2>
<p class="post-meta post-tags">{% if post.author %}{{ post.author }} • {% endif %}{% if post.tags %}{% for tag in post.tags %}<span class = "post-tag">{{ tag }}</span>&nbsp;{% endfor %}{% endif %}{% if post.meta %} • {{ post.meta }}{% endif %}</p>
{{ post.excerpt }}
	
	<!-- <div class = "post-tags">
  	  {% for tag in post.tags %}
        <span class = "post-tag">{{ tag }}</span>&nbsp;
      {% endfor %}
	</div> -->
  </li>
{% endfor %}
</ul>
