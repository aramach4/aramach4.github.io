---
title: "Projects"
layout: single
excerpt: "Descriptions of my research projects"
sitemap: true
permalink: /projects/
frontpageorder: 3
categories: [frontpage]
author_profile: true
---

{% for page in site.pages %}
{% if page.categories contains 'project' %}
<h2><a href="{{page.permalink}}">{{page.title}}</a></h2>
{{page.excerpt}}
{% endif %}
{% endfor %}
