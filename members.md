---
title: Madres

---

# Madres


{% for member in site.members %}
  ## {{ member.name }} - {{ member.position }}
  [ver]({{ member.url }}) 
  {{ member.content | markdownify }}
{% endfor %}


{% for madre in site.data.madres %}
  ## {{ madre.nombre }} - {{ madre.edad }} - {{ madre.sexo }}
{% endfor %}
