---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About

I am Haoyu Li (李皓宇), a PhD student at the University of Illinois Urbana-Champaign advised by <a href="https://www.xing-luyi.com/" target="_blank" rel="noopener noreferrer">Prof. Luyi Xing</a> since 2025 Fall. 

I obtained my bachelor's and master's degrees at Shanghai Jiao Tong University.
<!-- https://en.sjtu.edu.cn/ -->


## Publications

{% for post in site.publications reversed %} {% if post.selected %} {% include archive-paper.html %} {% endif %} {% endfor %}


## Work Experience

{% for post in site.work reversed %} {% include archive-work-experience.html %} {% endfor %}


## Teaching Experience

{% for post in site.teaching reversed %} {% include archive-teaching.html %} {% endfor %}