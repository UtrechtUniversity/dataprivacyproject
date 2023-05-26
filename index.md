---
title: Home
#feature_text: <h2>Data Privacy Project</h2>
feature_image: "assets/images/header2.png"
#excerpt: "Description"
aside: true
---

Welcome to the landing page of the Data Privacy Project!

The Data Privacy Project was a data support effort within Utrecht University, the Netherlands. It was funded by Utrecht University's (FAIR) Research IT program and a Digital Competence Center grant from the Dutch Organization for Scientific Research (NWO).

The aim of the project was to develop multidisciplinary knowledge of, tools about, and experience with how researchers can and should deal with personal data, with an emphasis on practical techniques, computational tools, legal policies and user experiences. 

<a href="deliverables" class="button">Find out what we accomplished</a>

### Latest news
<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <b><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></b> ({{ post.date | date_to_string }})<br>
      <p>{{ post.summary }}</p>
    </li>
  {% endfor %}
</ul>