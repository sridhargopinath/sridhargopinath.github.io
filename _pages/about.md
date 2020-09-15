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

I am an MS in CS student at UT Austin expected to graduate in May 2021. I am looking for full-time opportunities.

I am excited about program verification and compilers. I am interested in working on improving the performance and reliability of products that have a real-world impact. I have worked on improving the reliability of Apple's GPU compiler and also [Windows 10 device drivers](https://www.microsoft.com/en-us/research/project/angelic-verification/). I have also worked on Microsoft's [EdgeML](https://microsoft.github.io/EdgeML/) framework to compile machine learning models to high-performant C code to run on embedded IoT devices.

# Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
