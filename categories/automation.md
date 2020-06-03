---
layout: page
title: Test Automation
permalink: /blog/categories/automation/
---

<h5 class="mt-3"> Posts by Category : {{ page.title }} </h5>


<div class="card">
{% for post in site.categories.automation %}
 <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>

