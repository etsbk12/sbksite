---
layout: main
title: Simböck IT Beratung / Bisherige Projekte
---

## Projekte

{% for project in site.data.projects %}
      
- **{{ project.name }}**
{{ project.desc }}

{% endfor %}