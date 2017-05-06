---
title: index
last_updated: 6 May 2017
permalink: index.html
---

# A Bit About Me
- I am a Spring 2017 graduate of Ferris State University's Information Security and Intelligence (ISI) program.
- My scripting language of choice is Python.
- My favorite pastimes are Internet archeology and finding out how things work.

# Certifications
- Certified Ethical Hacker (C\|EH)
- Cellebrite Certified Operator (COO)

# Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
