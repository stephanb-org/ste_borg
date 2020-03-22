---
layout: default
title: Home
---

# Hello, friend.

> Hello, friend? That's lame. Maybe I should give you a name.

<div class="alert alert-warning" role="alert">
  Work in progress.
</div>

You have discovered the Stephan Borg's web page. Description provided at the end of the menu. 

Updates frequency is incosistent and, content topics are broad. Here is what I have been up to:

  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>

Here is a **road map** of what I am brewing:

* Reading Wishlist
* Gear & Equipment
* Donate
* Subcribe for Newsletter

Last updated: 2020-03-22

 _*Mr.Robot Intro_
