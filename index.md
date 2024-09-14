---
layout: home  # Use your default layout or create a custom one
title: "Welcome to Azure Minds"
permalink: /
---

# Welcome to Azure Minds

Writing about all things machine learning and data engineering.

## About Me

Hello! I'm Patrick Stewart, a data engineer and machine learning enthusiast. I love exploring the intersections of data science, machine learning, and natural language processing.

## Latest Posts

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}