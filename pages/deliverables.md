---
layout: page
title: Project deliverables
permalink: deliverables
feature_image: "assets/images/header2.png"
---
<aside class="aside  typeset  aside--{{ include.align | default: 'left' }}">
    <ul>
        {% for item in site.data.navigation.deliverables %}
          <li>
            <a href="{{ item.url }}">{{ item.page }}</a>
          </li>
        {% endfor %}
    </ul>
</aside>

Click on the menu to read more about each individual project deliverable.

## Quick links
<a href="https://utrechtuniversity.github.io/dataprivacyhandbook/" target="_blank" class="button">Data Privacy Handbook</a><br>
<a href="https://github.com/UtrechtUniversity/dataprivacyhandbook/#readme" target="_blank" class="button">Data Privacy Handbook GitHub repository</a><br>
<a href="https://utrechtuniversity.github.io/dataprivacyproject/assets/docs/Call_for_use_cases.pdf" target="_blank" class="button">Call for research projects with data privacy issues</a>
