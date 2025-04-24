---
permalink: /
title: ""
author_profile: true
---

Welcome! I am a Ph.D. candidate in the Department of Political Science at the University of Iowa, where I research political media habits, public opinion, and political behavior in the United States. My work focuses on the intersection of political media habits, public opinion, and democratic engagement, with an emphasis on how everyday media consumption shapes political behavior, deepens societal divides, and affects mental well-being in the United States.

Through this site, I share updates on my research, ongoing projects, and academic work. If you have any questions or inquiries, please feel free to [contact me](mailto:simal-gerot@uiowa.edu)!




<h2 style="font-size: 1.4em;">Latest Updates</h2>

<div style="font-size: 0.95em; line-height: 1.5;">

{% for post in site.posts limit:3 %}
  <p>
    <strong><a href="{{ post.url }}">{{ post.title }}</a></strong><br>
    <em>{{ post.date | date: "%B %d, %Y" }}</em><br>
    {{ post.excerpt | strip_html | truncate: 150 }} 
    <a href="{{ post.url }}">Read more →</a>
  </p>
  <hr style="margin: 10px 0;">
{% endfor %}

</div>
