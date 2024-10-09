---
layout: page
title: People
permalink: /people/
tags: people
---

<h1> ARMLab People </h1>


{% assign posts_count = site.people | size %}

<div class="home">

<h2>Professor</h2> <br>

<div class="posts">
      {% for post in site.people %}
      {% if post.person == "prof" %}
      <div class="person-card">
            <img src="images/{{ post.image }}" alt="{{ post.name }}" class="profile-image">
            <div class="person-info">
                <h2 class="person-name">{{ post.name }}</h2>
                <div class="social-icons">
                    <a href="{{ post.website }}"><i class="fas fa-home"></i></a>
                    <a href="https://github.com/{{ post.github }}"><i class="fab fa-github"></i></a>
                    {% if post.scholar %}
                        <a href="https://scholar.google.com/citations?user={{ post.scholar }}&hl=en"><i class="fas fa-graduation-cap"></i></a>
                    {% endif %}
                </div>
                <p class="person-description">{% if post.summary %}
              {{ post.summary }}
            {% else %}
              {{ post.excerpt }}
            {% endif %}</p>
            </div>
    </div>
    {% endif %}
      {% endfor %}
    </div>

<!-- <h3>Postdoc</h3> <br> -->

<h3>PhD Students</h3>


  {% if posts_count > 0 %}
    <div class="posts">
      {% for post in site.people %}
      {% if post.person == "phd" %}
      <div class="person-card">
            <img src="images/{{ post.image }}" alt="{{ post.name }}" class="profile-image">
            <div class="person-info">
                <h2 class="person-name">{{ post.name }}</h2>
                <div class="social-icons">
                {% if post.website %}
                    <a href="{{ post.website }}"><i class="fas fa-home"></i></a>
                {% endif %}
                {% if post.linkedin %}
                    <a href="{{ post.linkedin }}"><i class="fa fa-linkedin"></i></a>
                {% endif %}
                    {% if post.github %}
                    <a href="https://github.com/{{ post.github }}"><i class="fab fa-github"></i></a>
                    {% endif %} 
                    {% if post.scholar %}
                        <a href="https://scholar.google.com/citations?user={{ post.scholar }}&hl=en"><i class="fas fa-graduation-cap"></i></a>
                    {% endif %}
                </div>
                <p class="person-description">{% if post.summary %}
              {{ post.summary }}
            {% else %}
              {{ post.excerpt }}
            {% endif %}</p>
            </div>
    </div>
    {% endif %}
      {% endfor %}
    </div>
    <h3> Master's Students </h3>
    <div class="posts">
      {% for post in site.people %}
      {% if post.person == "master" %}
      <div class="person-card">
            <img src="images/{{ post.image }}" alt="{{ post.name }}" class="profile-image">
            <div class="person-info">
                <h2 class="person-name">{{ post.name }}</h2>
                <div class="social-icons">
                    {% if post.website %}
                        <a href="{{ post.website }}"><i class="fas fa-home"></i></a>
                    {% endif %}
                    {% if post.github %}
                    <a href="https://github.com/{{ post.github }}"><i class="fab fa-github"></i></a>
                    {% endif %}
                    {% if post.scholar %}
                        <a href="https://scholar.google.com/citations?user={{ post.scholar }}&hl=en"><i class="fas fa-graduation-cap"></i></a>
                    {% endif %}
                </div>
                <p class="person-description">{% if post.summary %}
              {{ post.summary }}
            {% else %}
              {{ post.excerpt }}
            {% endif %}</p>
            </div>
    </div>
    {% endif %}
      {% endfor %}
    </div>
    <h3> Undergraduate Students </h3>
    <div class="posts">
      {% for post in site.people %}
      {% if post.person == "undergrad" %}
      <div class="person-card">
            <img src="images/{{ post.image }}" alt="{{ post.name }}" class="profile-image">
            <div class="person-info">
                <h2 class="person-name">{{ post.name }}</h2>
                <div class="social-icons">
                    {% if post.website %}
                        <a href="{{ post.website }}"><i class="fas fa-home"></i></a>
                    {% endif %}
                    {% if post.github %}
                    <a href="https://github.com/{{ post.github }}"><i class="fab fa-github"></i></a>
                    {% endif %}
                    {% if post.scholar %}
                        <a href="https://scholar.google.com/citations?user={{ post.scholar }}&hl=en"><i class="fas fa-graduation-cap"></i></a>
                    {% endif %}
                </div>
                <p class="person-description">{% if post.summary %}
              {{ post.summary }}
            {% else %}
              {{ post.excerpt }}
            {% endif %}</p>
            </div>
    </div>
    {% endif %}
      {% endfor %}
    </div>
    <h3> PhD and Postdoc Alumni </h3>
    <div class="posts">
      {% for post in site.people %}
      {% if post.person == "alumni_phd" %}
      <div class="person-card">
            <img src="images/{{ post.image }}" alt="{{ post.name }}" class="profile-image">
            <div class="person-info">
                <h2 class="person-name">{{ post.name }}</h2>
                <div class="social-icons">
                    {% if post.website %}
                        <a href="{{ post.website }}"><i class="fas fa-home"></i></a>
                    {% endif %}
                    {% if post.github %}
                    <a href="https://github.com/{{ post.github }}"><i class="fab fa-github"></i></a>
                    {% endif %}
                    {% if post.scholar %}
                        <a href="https://scholar.google.com/citations?user={{ post.scholar }}&hl=en"><i class="fas fa-graduation-cap"></i></a>
                    {% endif %}
                </div>
                <p class="person-description">{% if post.summary %}
              {{ post.summary }}
            {% else %}
              {{ post.excerpt }}
            {% endif %}</p>
            </div>
    </div>
    {% endif %}
      {% endfor %}
    </div>
    <h3> MS and Undergraduate Alumni </h3>

    

    {% include pagination.html %}
  {% else %}
    <h1 class='center'>{{ site.text.index.coming_soon }}</h1>
  {% endif %}



</div>
