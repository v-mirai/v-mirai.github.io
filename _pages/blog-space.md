---
layout: single
title: "Blog Space"
author: Venkatesan Sudalaimani
permalink: /blog-space/
author_profile: true
sidebar:
    -image: "/assets/images/blog-1.JPG"
og_image: "/assets/images/blog-1.JPG"
---


It is always a strange experience to be able to look at things from another's perspective. To me, reading blog posts give me an opportunity to do just that. I believe if people can look through each other's eyes without initial judgement, it is possible to obtain clarity on a subject under the spotlight. The argument that comes after that, is the best kind. The kind that solves a problem. The kind that gives us a sort of a complete picture. 


{% include figure image_path="assets/images/perspective.JPG" alt="(Artwork courtesy of https://www.trinitydt.org/)" caption="Perspective!" %}

Here you will find my observations on some everyday things that caught my attention. Some of it might be cool to you and some may be just silly. If you feel like it, give it a read and I would be more than happy to hear your comments!


<div class="grid__wrapper">
  {% assign posts = site.posts %}
  {% for post in posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>