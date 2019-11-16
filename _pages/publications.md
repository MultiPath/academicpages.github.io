---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my [Google Scholar Profile](https://scholar.google.com/citations?user=cB1mFBsAAAAJ)<br>
(^: Equal Contribution)

{% include base_path %}

## Pre-prints (In progress)
{% for post in site.arxiv reversed %}
  {% include archive-single.html %}
{% endfor %}

## Conference Papers
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Journal Papers
{% for post in site.journals reversed %}
  {% include archive-single.html %}
{% endfor %}

