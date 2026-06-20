---
title: Welcome
pin: true
layout: page
icon: fas fa-home
order: 1
---

# Welcome

I am Nia Aristo, a Solutions Engineer at Cisco focused on helping organizations modernize their infrastructure through cloud-native technologies, observability, and automation.

## Areas of Expertise

- Cloud Architecture
- Kubernetes
- DevOps
- Platform Engineering
- Observability
- Site Reliability Engineering

## 📌 Latest Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
