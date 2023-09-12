# Progetti

<div style="display: flex; flex-wrap: wrap; gap: 1em;">
  {% for project in site.projects %}
    <a href="{{ project.url | relative_url }}" style="flex: 0 0 calc(50% - 0.5em);">
      <figure style="margin: 0;">
        <img src="{{ project.images | first | relative_url }}" />
        <figcaption>{{ project.title | smartify }}</figcaption>
      </figure>
    </a>
  {% endfor %}
</div>
