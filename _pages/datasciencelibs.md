---
layout: archive
permalink: /data-science-lib/
title: "Data Analysis - Python Libraries"
author_profile: true
header:
    image: "images/code_wide_1.jpg"
---


{% include group-by-array collection=site.posts field="tags" %}

{% for tag in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ tag | slugify }}" class="archive__subtitle">{{ tag }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}