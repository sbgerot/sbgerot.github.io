---
permalink: /
title: ""
author_profile: true
---

Welcome! I am a Ph.D. candidate in the Department of Political Science at the University of Iowa and currently a CLAS Dissertation Writing Fellow. My research focuses on the intersection of political media habits, public opinion, and democratic engagement, with an emphasis on how everyday media consumption shapes political behavior, deepens societal divides, and affects mental well-being in the United States.

My research has received support through several fellowships and awards, among which are the [CLAS Dissertation Writing Fellowship](https://clas.uiowa.edu/academics/graduate-education/funding/clas-dissertation-writing-fellowships#accordion-item-4266-0) and the [Graduate College Post-Comprehensive Research Fellowship](https://grad.uiowa.edu/funding/fellowships/post-comp). It was also recently featured in the [CLAS April Newsletter](https://clas.uiowa.edu/news/2025/04/meet-these-clas-student-researchers?utm_medium=email&utm_content=Meet+these+CLAS+student+researchers&utm_source=d.clas.webservices&utm_campaign=Research+Resource&utm_id=1109169277.1416865768), as part of a feature on CLAS student researchers, which highlighted my research on how everyday news media habits influence mental well-being, political beliefs, and societal divides.




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
