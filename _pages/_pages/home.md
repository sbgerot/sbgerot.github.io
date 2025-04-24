---
permalink: /
title: ""
author_profile: true
---

Welcome! I am a Ph.D. candidate in the Department of Political Science at the University of Iowa, where I research political media habits, public opinion, and political behavior in the United States. My work focuses on the intersection of political media habits, public opinion, and democratic engagement, with an emphasis on how everyday media consumption shapes political behavior, deepens societal divides, and affects mental well-being in the United States.

Through this site, I share updates on my research, ongoing projects, and academic work. If you have any questions or inquiries, please feel free to [contact me](mailto:simal-gerot@uiowa.edu)!






<hr>

<div style="max-width: 700px; margin-top: 30px;">
  <h3 style="font-size: 1rem; margin-bottom: 1rem;">Latest Updates</h3>

  {% for post in site.posts limit:3 %}
    <div style="margin-bottom: 20px; font-size: 1rem;">
      <p style="margin-bottom: 4px;">
        <a href="{{ post.url }}" style="font-weight: bold;">{{ post.title }}</a><br>
        <span style="font-style: italic;">{{ post.date | date: "%B %d, %Y" }}</span>
      </p>
      <p style="margin-bottom: 5px;">
        {{ post.excerpt | strip_html | truncatewords: 20 }} 
        <a href="{{ post.url }}">Read more →</a>
      </p>
    </div>
  {% endfor %}
</div>
