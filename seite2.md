---
layout: main
title: Simböck IT Beratung / Bisherige Projekte
---

## Projekte

{% for project in site.data.projects %}
      
-   **{{ project.name }}**
    Themen: {{ project.desc }}
    Mein Anteil: {{ project.mypart }}

{% endfor %}