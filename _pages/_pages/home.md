---
permalink: /
title: ""
author_profile: true
---

Welcome! I am a Ph.D. candidate in the Department of Political Science at the University of Iowa, where I research political media habits, public opinion, and political behavior in the United States. My work focuses on the intersection of political media habits, public opinion, and democratic engagement, with an emphasis on how everyday media consumption shapes political behavior, deepens societal divides, and affects mental well-being in the United States.

Through this site, I share updates on my research, ongoing projects, and academic work. If you have any questions or inquiries, please feel free to [contact me](mailto:simal-gerot@uiowa.edu)!




<div style="background: #f9f9f9; padding: 20px; border-radius: 6px; margin-top: 30px;">

<span style="font-size: 1.1em;">Latest Updates</span>

<ul style="list-style-type: none; padding-left: 0;">
  {% for post in site.posts limit:3 %}
    <li style="margin-bottom: 20px;">
      <a href="{{ post.url }}" style="font-weight: bold;">{{ post.title }}</a> <br>
      <span style="font-style: italic; font-size: 0.9em;">{{ post.date | date: "%B %d, %Y" }}</span>
      <p style="margin: 5px 0 0 0;">{{ post.excerpt | strip_html | truncate: 160 }} <a href="{{ post.url }}">Read more →</a></p>
    </li>
  {% endfor %}
</ul>

</div>
