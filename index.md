---
layout: home
title: Welcome to keflings korner!
theme: minima
---

A collection of half-baked whims and fancies in no particular order



<figure>
    <img src="/images/Garfield_and_Odie_Trick_Or_Treating.jpg" width="300" height="250"
         alt="Garfield_and_Odie_Trick_Or_Treating">
    <figcaption> It's spooky season.</figcaption>
</figure>



# Index

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
{% endfor %}
