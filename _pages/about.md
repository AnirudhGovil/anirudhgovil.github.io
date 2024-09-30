---
permalink: /
title: "Anirudh Govil"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I work as a Computer Vision Research Engineer at [DreamVu](https://dreamvu.com/). A day of work would see me read the latest work in the area, scientifically test the image processing pipelines that perform depth detection and semantic segmentation and propose improvements to the same.

I previously worked as a Computer Vision Engineer at [Game Theory](https://www.gametheory.in/) where I built the core calibration, traingulation and detection pipelines for shuttles/ball tracking in sports videos.

<h3>News</h3>
{% assign news = site.data.news | where: "hidden", nil | sort: 'date' | reverse | slice: 0, 7 %}
{% include news.html news=news %}


<h3>Publications</h3>
{% include publications.html
    publications=site.data.publications
    numbering=false
%}

I've had the pleasure of being advised by [Madahava Krishna](), [Ponnurangam Kumaraguru](https://precog.iiit.ac.in/) and [](https://saujasv.github.io/), and [Saourav Garg](), as I worked on Semantic Segmentation, Vision Language Models, Robotic Control and Codemixing in NLP.
