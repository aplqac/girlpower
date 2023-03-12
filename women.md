---
layout: default
permalink: /women/index.html
---
# Women in STEM
{% for woman in site.women %}
  <h2>
      {{ woman.name }}
  </h2>
  ![Woman](/girlpower/assets/images/{{ woman.image }})
  <p>{{ woman.content | markdownify }}</p>
{% endfor %}

## Other Important Women in STEM
[![Mae Jemison](https://img.youtube.com/vi/rWxGAogqr4M/0.jpg)](https://www.youtube.com/watch?v=rWxGAogqr4M)
[![Marie Curie](https://img.youtube.com/vi/w6JFRi0Qm_s/0.jpg)](https://www.youtube.com/watch?v=w6JFRi0Qm_s)
[![Grace Hopper](https://img.youtube.com/vi/EG0Y8BfA4o0/0.jpg)](https://www.youtube.com/watch?v=EG0Y8BfA4o0)
