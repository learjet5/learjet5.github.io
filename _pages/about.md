---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About

I am Haoyu Li (李皓宇), a PhD student at the University of Illinois Urbana-Champaign (<a href="https://illinois.edu/" target="_blank" rel="noopener noreferrer">UIUC</a>) advised by <a href="https://www.xing-luyi.com/" target="_blank" rel="noopener noreferrer">Prof. Luyi Xing</a> since 2025 Fall. \\
My research interests span **system security** and **machine learning**, with a particular focus on identifying emerging security flaws in complex systems and leveraging LLMs for more accurate and efficient code analysis.

Prior to UIUC, I obtained my bachelor's and master's degrees at <a href="https://en.sjtu.edu.cn/" target="_blank" rel="noopener noreferrer">SJTU</a>, 
working with <a href="https://scholar.google.com/citations?hl=zh-CN&user=7ikP578AAAAJ" target="_blank" rel="noopener noreferrer">Libo Chen</a> and playing CTF with <a href="https://ctftime.org/team/4419" target="_blank" rel="noopener noreferrer">0ops</a>.

## Publications

{% for post in site.publications reversed %} {% if post.selected %} {% include archive-paper.html %} {% endif %} {% endfor %}

## Work Experience

<!-- To be beautified. -->
{% for post in site.work reversed %} {% include archive-work-experience.html %} {% endfor %}

## Academic Service

Sub-reviewer: USENIX Security’26, NDSS’26.

## Teaching Experience

{% for post in site.teaching reversed %} {% include archive-teaching.html %} {% endfor %}

<!-- Considering add a CVD list -->
<!-- News -->
<!-- Awards -->

<!-- jekyll serve -l -H localhost -->