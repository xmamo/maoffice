---
layout: 'default'
---

# Progetti

<div style="display: flex; flex-wrap: wrap; gap: 1em;">
  {% for project in site.projects %}
    <a href="{{ project.url | relative_url }}" style="width: calc(50% - 0.5em);">
      <figure style="height: 100%; margin: 0; display: flex; flex-direction: column;">
        <img src="{{ project.images | first | relative_url }}" class="cover" style="width: 100%; flex: 1 0;" />
        <figcaption style="white-space: nowrap; overflow: hidden; text-overflow: ellipsis;">{{ project.title | smartify }}</figcaption>
      </figure>
    </a>
  {% endfor %}
</div>
