---
layout: page
title: People
permalink: /people/
tags: people
---

<h1>ARMLab People</h1>

<div class="home">

  <h2>Professor</h2>
  <div class="posts">
    {% for post in site.people %}
      {% if post.person == "prof" %}
        {% include person_card.html person=post %}
      {% endif %}
    {% endfor %}
  </div>

  <h2>PhD Students</h2>
  <div class="posts">
    {% for post in site.people %}
      {% if post.person == "phd" %}
        {% include person_card.html person=post %}
      {% endif %}
    {% endfor %}
  </div>

  <h2>Master's Students</h2>
  <div class="posts">
    {% for post in site.people %}
      {% if post.person == "master" %}
        {% include person_card.html person=post %}
      {% endif %}
    {% endfor %}
  </div>

  <h2>Undergraduate Students</h2>
  <div class="posts">
    {% for post in site.people %}
      {% if post.person == "undergrad" %}
        {% include person_card.html person=post %}
      {% endif %}
    {% endfor %}
  </div>

  <h2>PhD and Postdoc Alumni</h2>
  <div class="posts">
    {% for post in site.people %}
      {% if post.person == "alumni_phd" %}
        {% include person_card.html person=post %}
      {% endif %}
    {% endfor %}
  </div>

  <h2>MS and Undergraduate Alumni</h2>
  <div class="posts">
    {% for post in site.people %}
      {% if post.person == "alumni_ms" %}
        {% include alumni_card.html person=post %}
      {% endif %}
    {% endfor %}
  </div>

</div>

{% include pagination.html %}
