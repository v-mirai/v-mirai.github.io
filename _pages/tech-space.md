---
layout: single
title: "Tech Space"
author: Venkatesan Sudalaimani
permalink: /techspace/
author_profile: true
sidebar:
    -image: "/assets/images/tech-space-3.JPG"
og_image: "/assets/images/tech-space-3.JPG"
---

Years of comics, novels, cartoons, and movies made me a sucker for Magic and there was a time when I wanted to be a magician. And yes, I do know most of them are tricks and "there is a perfectly reasonable explanation for it all". What intrigues me is the unknown element that creates the illusion of magic. In a way we could say the magicians are paid con artists while the audience are merely an ignorant crowd. But why am I talking about magic you wonder?

Perhaps you have heard this famous quote from Arthur C. Clarke,

> *"Any sufficiently advanced technology is indistinguishable from Magic"*

{% include figure image_path="assets/images/calvin-hobbes-magic.JPG" alt="(PC: CalvinandHobbes)" caption="Magic and Technology" %}

See the connection?  This is a quote that will remain true at every era of human history. Imagine if we can travel back to the end of 1600s(today's magic) and demonstrate communication via radio transmitter and receiver. We would either be God's men with mystical powers or be put on stakes and burnt alive for practicing witchcraft. But today, it is as trivial as pineapples on a pizza (yup, I am one of them).

Just as I realized magic was a well crafted trick using Science and Technology, I came to see prominent Scientists, Engineers, and Inventors as the modern wizards. And being a practitioner of the art, I am on a journey to understand tricks of the trade of today and to apply them in my day to day life.

In this space, you will find some of my technical experiences and articles that cover the areas of generic programming, Basic CS (Data Structures and Algorithms, Operating Systems) and the fascinating field of artificial intelligence. I would be happy to hear any sort of feedback (criticisms included) on my work.

Happy reading!

## Latest Articles

<div class="grid__wrapper">
  {% assign collection = 'tech-space' %}
  {% assign posts = site[collection] | reverse %}
  {% for post in posts %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>