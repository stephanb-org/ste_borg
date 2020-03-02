---
layout: default
title: Home
---

# Hello, friend.

> Hello, friend? That's lame. Maybe I should give you a name.*

You have discovered the web page of Stephan Borg. Description provided at the end of the menu. 

Updates frequency is incosistent and, content topics are broad. Here is what I have been up to:

  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
It is still a <span class="text-danger">work in progress</span>. Nonetheless, here is a **road map** of what I am brewing:

* Reading Wishlist
* Gear & Equipment
* Donate
* Subcribe for Newsletter


 _*Mr.Robot Intro_
