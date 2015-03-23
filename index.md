---
layout: archive
permalink: /
title: "HOME"
image:
 feature: feature-homev1ll0.png
---

The purpose of this page is to present and describe the projects in which I contributed. Every projects has a title, a description and a link to the project itself.

<span style="color:red;">Work in Progress</span>

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
