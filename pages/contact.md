---
layout: page
title: "Contact"
date: 2022-02-10 10:10:15 -0700
author: Lucky
categories: jekyll
feature-img: "assets/img/pexels/book-glass.jpeg"
permalink: /:catergories/:date/:year/:month//:title/
---
<body style="background-color:lightblue;">
<h3 style="text-align:center;">{{page.author}}</h3>
<pre>
<p style="color:pink;">If you have any questions or want to reach out please 
<a href="mailto:someone@example.com"> send email</a> to me .</p>
</pre>

{% include aligner.html images="pexels/computer.jpeg" %}

![Image]({{ "assets/img/pexels/travel.jpeg" | relative_url}})

<img src="assets/img/pexels/travel.jpeg" alt=" travel pic" style= "float:right;" >
</body>