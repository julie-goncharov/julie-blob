---
layout: default
title: Contact
permalink: /contact/
---

<h1>Contact me</h1>
<h2>Office</h2>
Nikolausberger Weg 23, room 2.106

37073 Göttingen

<h2>Email</h2>
julie dot goncharov at uni-goettingen dot de

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

