---
layout: page
title: Publications
permalink: /publications/
tags: publications
---

<h1>Publications</h1>

<div class="publications">
  {% for paper in site.data.papers %}
    {% include paper_entry.html paper=paper %}
  {% endfor %}
</div>
