---
title: MOC - Glossary
---

Glossary in the domain of information systems research.

<strong>Map of Concepts (MOCs)</strong>

<ul>
  {% assign glo_notes = site.notes %}
  {% for note in glo_notes %}
    <!-- <a>{{ note.url }}</a> -->
    {% if note.url contains "/glo" %}
    <li>
        <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
    {% endif %}
  {% endfor %}
</ul>


