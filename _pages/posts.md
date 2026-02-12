---
title: Posts
layout: posts
permalink: /blog/posts/
author_profile: true
---

{% include group-by-array collection=site.posts field="year" %}

{% for year in group_names %}
  <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
  {% assign posts = group_items[forloop.index0] %}
  <p><strong>{{ posts | size }}</strong> posts</p>

  <div class="entries-list">
    {% for post in posts %}
      {% include archive-single.html type="list" %}
    {% endfor %}
  </div>
{% endfor %}
