---
layout: page
title: Home
id: home
permalink: /
---

# Welcome to My Mind Place 👋

<p style="padding: 2em 1em; background: #f5f7ff; border-radius: 4px;">
"Doublethink means the power of holding two contradictory beliefs in one's mind simultaneously, and accepting both of them."
<br><span style="font-weight: bold">― George Orwell, 1984</span>
</p>

This is my mind place to organize and publish my notes and thoughts in a digital garden style. As a PhD student, my main focus is on conversational AI. But of course the content is not limited to this domain. Feel free to look around and find something you like.

<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
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
