---
title: Home
#feature_text: <h2>Data Privacy Project</h2>
feature_image: "assets/images/header2.png"
#excerpt: "Description"
aside: true
---

Welcome to the landing page of the Data Privacy Project!

The Data Privacy Project is a data support effort within Utrecht University, the Netherlands. We are funded by Utrecht University's Research IT program and a Digital Competence Center grant from the Dutch Organization for Scientific Research (NWO).

Our aim is to develop multidisciplinary knowledge of, tools about, and experience with how researchers can and should deal with personal data, with an emphasis on practical techniques, computational tools, legal policies and user experiences.

### Latest news
<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <b><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></b> ({{ post.date | date_to_string }})<br>
      <p>{{ post.summary }}</p>
    </li>
  {% endfor %}
</ul>