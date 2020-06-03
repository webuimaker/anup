---
layout: page
title: Testing Concepts
permalink: /blog/categories/testing/
---

<h5 class="mt-3"> Posts by Category : {{ page.title }} </h5>


<div class="card">
{% for post in site.categories.testing %}
 <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>

