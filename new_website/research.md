---
layout: page
title: Research
permalink: /research/
tags: research
---

The broad research objective of the Assistive Robotics and Manipulation Lab is to develop technology that improves everyday life by anticipating and acting on the needs of human counterparts. We specialize in developing intelligent robotic systems that can perceive and model environments, humans and tasks and leverage these models to predict system processes and understand their assistive role. The research can be divided into the following sub-categories: robotic assistants, connected devices and intelligent wearables.  We use a combination of tools in dynamical systems analysis, control theory (classical, non-linear and robust control), state estimation and prediction, motion planning, vision for robotic autonomy and machine learning. Our lab focuses heavily on both the analytical and experimental components of assistive technology design. While our application area domain is autonomous assistive technology, our primary focus is robotic assistants (mobile manipulators and humanoids) with the goal of deployment for service tasks that may be highly dynamic and require dexterity, situational awareness, and human-robot collaboration.



<b>Research Topics</b>

{% assign posts_count = site.posts | size %}

<div class="home">
  {% if posts_count > 0 %}
    <div class="posts">
      {% for post in site.posts %}
        <div class="post py3">
          <a href="{{ post.url | relative_url }}" class="post-link"><h3 class="h1 post-title">{{ post.title }}</h3></a>
          <span class="post-summary">
            {% if post.summary %}
              {{ post.summary }}
            {% else %}
              {{ post.excerpt }}
            {% endif %}
          </span>
        </div>
      {% endfor %}
    </div>

    {% include pagination.html %}
  {% else %}
    <h1 class='center'>{{ site.text.index.coming_soon }}</h1>
  {% endif %}
</div>