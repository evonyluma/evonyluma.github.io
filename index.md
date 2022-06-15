---
layout: default
title: News
nav_order: 1
---
# TOR Alliance Website

This is the web repository of the TOR alliance.

## Latest News

<ul class="posts">
   {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
   {% endfor %}
</ul>
