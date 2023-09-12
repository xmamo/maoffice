---
layout: 'default'
---

# Progetti

<div style="display: flex; flex-wrap: wrap; gap: 1em;">
  {% for project in site.projects %}
    <a href="{{ project.url | relative_url }}" style="width: calc(50% - 0.5em);">
      <figure class="h-100" style=" margin: 0; display: flex; flex-direction: column;">
        <img src="{{ project.images | first | relative_url }}" class="w-100 cover" style="flex: 1 0;" />
        <figcaption style="white-space: nowrap; overflow: hidden; text-overflow: ellipsis;">{{ project.title | smartify }}</figcaption>
      </figure>
    </a>
  {% endfor %}
</div>
