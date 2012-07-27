---
layout: page
title: HiØ dev guides
tagline: Guides to get started developing the Østfold University College web and mobile platform
---
{% include JB/setup %}

## Table of Contents


1.  Introduction

2.  Installation 

    2.1 Installation on Mac 

    2.2 Installation on Windows

    (development of the iOS application require a mac)

    2.4 Installation on Linux

3.  Versioning Policy

4.  License





## All posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

Our own design