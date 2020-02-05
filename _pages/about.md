---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# Homepage

Hi there! Welcome to my website. Here's a little bit about me.

I am a Ph.D. student at the University of Texas, Austin. I am advised by [Prof. Isil Dillig](http://www.cs.utexas.edu/~isil/). I am part of the [UToPiA lab](http://utopia.cs.utexas.edu/). My research interests are in programming languages and compilers.

Previously, I spent two amazing years at Microsoft Research, India as a Research Fellow. I worked with [Rahul Sharma](https://www.microsoft.com/en-us/research/people/rahsha/) in the [EdgeML](https://microsoft.github.io/EdgeML/) team.

# Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
