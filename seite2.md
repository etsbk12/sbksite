---
layout: main
title: Simböck IT Beratung / Bisherige Projekte
---

## Projekte

{% for project in site.data.projects %}
    <li>
      <h2>{{ project.name }}</h2>
      {{ project.desc }}
    </li>
{% endfor %}