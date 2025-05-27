---
permalink: /
excerpt: "About me"
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a postdoctoral researcher at the University of Cambridge at [The Department of Plant Sciences](https://www.plantsci.cam.ac.uk/directory/unnati-sonawala)/[Crop Science Centre](https://www.cropsciencecentre.org/staff/unnati-sonawala). 

I study plant-microbe interactions, and am currently working on deciphering the immune receptor network in Sweet Potato by probing it with root-knot nematodes. To learn more about current and past projects follow [here](projects). See [CV](cv) for a summary of my education and career. 

If not in the lab mixing colourless liquids or wrangling some 'omics data at the computer, I am out dancing tango. If not dancing tango, I am either learning a new language or at the piano. Contact me if you would like to talk about any of them!


<h3>Latest News</h3>
<ul>
  {% assign news_posts = site.news | sort: 'date' | reverse %}
  {% for post in news_posts limit:3 %}
    <li>
      <strong>{{ post.date | date: "%B %d, %Y" }}</strong>: 
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

