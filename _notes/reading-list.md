---
title: Reading List
---

## ⏳ Reading

- Foundations of Information Systems [[glo-is|IS]]
- Information Systems for Business and Beyond [[glo-is|IS]]
- Active Inference: The Free Energy Principle in Mind, Brain, and Behavior [Link](https://direct.mit.edu/books/oa-monograph/5299/Active-InferenceThe-Free-Energy-Principle-in-Mind)
- [[msis480|Management Information Systems]]
- [Information System Evolution](https://www.emerald.com/insight/content/doi/10.1108/978-1-80043-810-120211004/full/html)

## ✅ Read




## 📄 Paper


<ul>
  {% assign moc_notes = site.notes %}
  {% for note in moc_notes %}
    {% if note.type == "paper" %}
      <li>
        <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

