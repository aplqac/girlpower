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
<iframe width="506" height="315" src="https://www.youtube.com/watch?v=EgOaIKshbIU" frameborder="0" allowfullscreen></iframe>
<br>
<iframe width="506" height="315" src="https://www.youtube.com/watch?v=w6JFRi0Qm_s" frameborder="0" allowfullscreen></iframe>
<br>
<iframe width="506" height="315" src="https://www.youtube.com/watch?v=EG0Y8BfA4o0" frameborder="0" allowfullscreen></iframe>
