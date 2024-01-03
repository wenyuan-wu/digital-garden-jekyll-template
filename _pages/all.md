---
layout: page
title: All Notes
permalink: /all
---

# All Notes in Alphabetical Order

<ul>
  {% assign all_notes = site.notes | sort: "title" %}
  {% for note in all_notes%}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
