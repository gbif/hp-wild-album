---
layout: home
klass: home
lang-ref: home
permalink: /es/
title: Wild Album
description: Portal de datos de cámaras trampa
videos: ["/assets/images/wild-boar-inbo.mp4"]
imageLicense: "Jabalíes (adultos y jóvenes) capturados por una cámara trampa en Bélgica. Vídeo de INBO y UHasselt."
height: 60vh
composition:
  - type: heroVideo
  - type: stats
    inlineData:
      features:
        - title: <span data-ajax-url="https://api.gbif.org/v1/dataset/search?endpointType=CAMTRAP_DP">~10</span>
          description: Conjuntos de datos
          href: /es/dataset/search
        - title: <span data-ajax-path="data.occurrenceSearch.cardinality.speciesKey" data-ajax-url="https://graphql.gbif.org/graphql?query=query{occurrenceSearch(predicate:{key:%22protocol%22,type:equals,value:%22CAMTRAP_DP%22}){_predicate%20cardinality{speciesKey}}}">~350</span>
          description: Especies
          href: /es/occurrence/search?view=dashboard&layout=W1t7ImlkIjoiaG1sbHQiLCJwIjp7fSwidHJhbnNsYXRpb24iOiJkYXNoYm9hcmQudGF4YSIsInQiOiJ0YXhhIn1dXQ%3D%3D
        - title: <span data-ajax-url="https://api.gbif.org/v1/occurrence/search?protocol=CAMTRAP_DP&limit=0">~350,000</span>
          description: Registros
          href: /es/occurrence/search
  - type: split
    inlineData:
      title: Búsqueda de conjuntos de datos
      description: >
        Wild Album te ayuda a descubrir conjuntos de datos de fototrampeo publicados en [GBIF](https://www.gbif.org/es).
        Busca metadatos para encontrar conjuntos de datos relevantes para ti.
        O sumérgete en los datos de registros que estos conjuntos de datos contienen de manera colectiva.
      cta:
        - text: Explora los metadatos
          href: /es/dataset/search
        - text: Explora los registros
          href: /es/occurrence/search
      background: /assets/images/brown-bear-slu-BFR05.jpg
      imageLicense: Dos osos pardos (madre y cría de un año) capturados por una cámara trampa en Suecia. Imagen de SLU.
  - type: split
    inlineData:
      title: Haz que tus datos sean fáciles de encontrar
      description: >
        ¿Quieres que otros descubran los datos de tus cámaras trampa y los utilicen para investigación y conservación?
        Publica tu conjunto de datos en el estándar [Camtrap DP](https://camtrap-dp.tdwg.org) en [GBIF](https://www.gbif.org) y aparecerá automáticamente en este sitio web..
      cta:
        - text: Lee la guía de publicación
          href: https://doi.org/10.35035/doc-0qzp-2x37
        - text: Conviértete en editor
          href: https://www.gbif.org/es/become-a-publisher
      background: /assets/images/roe-deer-inbo.jpg
      imageLicense: Corzo capturado por una cámara trampa en Bélgica. Imagen de INBO.
      reverse: true
  - type: floatingText
    inlineData:
      klass: hp
      title: ¿Te interesan los datos de seguimiento de animales?
      description: >
        [Visita Wild Moves](https://moves.wildlabs.net/es){:.button}
      hasWhiteText: true
---
