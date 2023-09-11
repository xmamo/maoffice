---
figures:
  - caption: 'Banca Popolare di Cividale del Friuli'
    image: '/assets/images/banca-popolare-di-cividale-del-friuli/01.jpg'
    link: '/banca-popolare-di-cividale-del-friuli'

  - caption: 'Ex Albergo Operai'
    image: '/assets/images/ex-albergo-operai/01.gif'
    link: '/ex-albergo-operai'
  
  - caption: 'Museo Gugghenheim Helsinki'
    image: '/assets/images/guggenheim-helsinki-museum/01.jpg'
    link: '/guggenheim-helsinki-museum'
  
  - caption: 'Nuova Galleria Nazionale e museo Ludwig'
    image: '/assets/images/new-national-gallery-and-ludwig-museum/01.jpg'
    link: '/new-national-gallery-and-ludwig-museum'
  
  - caption: 'Palazzo Italia: concorso internazionale "Padiglione Italia Expo 2015"'
    image: '/assets/images/palazzo-italia-international-competition/01.jpg'
    link: '/palazzo-italia-international-competition'
  
  - caption: 'X Biennale di Venezia'
    image: '/assets/images/biennale-di-venezia/01.jpg'
    link: '/biennale-di-venezia'
---

# Progetti

<div style="display: flex; flex-wrap: wrap; gap: 1em;">
  {% for figure in page.figures %}
    <a href="{{ figure.link | relative_url }}" style="flex: 0 0 calc(50% - 0.5em);">
      <figure style="margin: 0;">
        <img src="{{ figure.image | relative_url }}" />
        <figcaption>{{ figure.caption | smartify }}</figcaption>
      </figure>
    </a>
  {% endfor %}
</div>
