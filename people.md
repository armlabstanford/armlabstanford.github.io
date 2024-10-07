---
layout: page
title: People
permalink: /people/
tags: people
---

The broad research objective of the Assistive Robotics and Manipulation Lab is to develop technology that improves everyday life by anticipating and acting on the needs of human counterparts. We specialize in developing intelligent robotic systems that can perceive and model environments, humans and tasks and leverage these models to predict system processes and understand their assistive role. The research can be divided into the following sub-categories: robotic assistants, connected devices and intelligent wearables.  We use a combination of tools in dynamical systems analysis, control theory (classical, non-linear and robust control), state estimation and prediction, motion planning, vision for robotic autonomy and machine learning. Our lab focuses heavily on both the analytical and experimental components of assistive technology design. While our application area domain is autonomous assistive technology, our primary focus is robotic assistants (mobile manipulators and humanoids) with the goal of deployment for service tasks that may be highly dynamic and require dexterity, situational awareness, and human-robot collaboration.



{% assign posts_count = site.people | size %}

<div class="home">

<b>Professor</b> <br>

<b>Postdoc</b> <br>

<b>PhD Students</b>


  {% if posts_count > 0 %}
    <div class="posts">
      {% for post in site.people %}
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
      {% endfor %}
    </div>
    <b> Master's Students </b>

    {% include pagination.html %}
  {% else %}
    <h1 class='center'>{{ site.text.index.coming_soon }}</h1>
  {% endif %}



</div>
