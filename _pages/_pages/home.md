---
permalink: /
title: ""
author_profile: true
---

Welcome! I am a Ph.D. candidate in the Department of Political Science at the University of Iowa, where I research political media habits, public opinion, and political behavior in the United States. My work focuses on the intersection of political media habits, public opinion, and democratic engagement, with an emphasis on how everyday media consumption shapes political behavior, deepens societal divides, and affects mental well-being in the United States.

Through this site, I share updates on my research, ongoing projects, and academic work. If you have any questions or inquiries, please feel free to [contact me](mailto:simal-gerot@uiowa.edu)!

## Latest Updates

<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
