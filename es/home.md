---
layout: home
klass: home
lang-ref: home
permalink: /es/
title: Wild Album
description: (es) Camera trap data portal
videos: ["/assets/images/wild-boar-inbo.mp4"]
imageLicense: "(es) Wild boars (adults and juveniles) captured by a camera trap in Belgium. Video by INBO and UHasselt."
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
        (es) Wild Album helps you discover camera trap datasets published to [GBIF](https://www.gbif.org/es).
        Search metadata to find datasets relevant to you.
        Or dive into the occurrence data these datasets collectively contain.
      cta:
        - text: Explora los metadatos
          href: /es/dataset/search
        - text: Explora los registros
          href: /es/occurrence/search
      background: /assets/images/brown-bear-slu-BFR05.jpg
      imageLicense: (es) Two brown bears (mother and yearling) captured by a camera trap in Sweden. Image by SLU.
  - type: split
    inlineData:
      title: Haz que tus datos sean fáciles de encontrar
      description: >
        (es) Want others to discover your camera trap data and use it for research and conservation?
        Publish your dataset in the [Camtrap DP](https://camtrap-dp.tdwg.org) standard to [GBIF](https://www.gbif.org)
        and it will automatically appear on Wild Album.
      cta:
        - text: (es) Read the publication guide
          href: https://doi.org/10.35035/doc-0qzp-2x37
        - text: Conviértete en editor
          href: https://www.gbif.org/es/become-a-publisher
      background: /assets/images/roe-deer-inbo.jpg
      imageLicense: (es) Roe deer captured by a camera trap in Belgium. Image by INBO.
      reverse: true
  - type: floatingText
    inlineData:
      klass: hp
      title: (es) Interested in animal tracking data?
      description: >
        [Visita Wild Moves](https://moves.wildlabs.net/es){:.button}
      hasWhiteText: true
---
