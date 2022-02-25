---
layout: page
title: Gallery
subtitle: From the pexels folder
permalink: /gallery/
gallery_path: "assets/img/pexels"
tags: [Page]
---
<hr style=" content: '§';display: inline-block;position: relative;top: -14px;padding: 0 10px;background: #f0f0f0;color: #8c8b8b;font-size: 18px;-webkit-transform: rotate(60deg);-moz-transform: rotate(60deg);transform: rotate(60deg);">

This is a photo gallery made from the static files in the `assets/img/pexels` folder. 
I wanted to create automatically a simple gallery from a folder without having to create a markdown page as you would for the portfolio.


{% include gallery.html gallery_path=page.gallery_path %}
