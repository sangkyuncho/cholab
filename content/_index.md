---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: Welcome to the group
        content: We are a team of scientists & engineers that studies how our cells interact with each other and with their physical microenvironment, particularly in the context of **fibrosis**---'scarring' of tissue that contributes to a vast range of human diseases.
        align: left
        background:
          image:
            filename: slide1.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Systems mechanobiology & <br>regenerative engineering
        content: We develop and apply methods in molecular biology, tissue/materials engineering, and data science to investigate fundamental biological questions and to develop solutions to pressing medical challenges.
        align: left
        background:
          image:
            filename: slide2.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Our mission
        content: Our long-term goal is to develop new **precision therapies** for treating fibrosis-associated diseases and conditions, which span cardiovascular disease, cancer, and aging.
        align: right
        background:
          image:
            filename: slide3.jpg
            filters:
              brightness: 1
          position: center
          color: '#333'
        link:
          icon: microscope
          icon_pack: fas
          text: Learn more about our work
          url: ../research/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: false
      slide_height: "84vh"
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 7000

  - block: collection
    id: pubs-list
    content:
      title: "Latest Publications"
      count: 2
      filters:
        author: ""
        tag: ""
        category: ""
        exclude_featured: false
      page_type: publication
      order: desc
    design:
      view: citation   # shows venue/journal
      columns: "1"
      spacing:
        padding: ['60px','0','40px','0']   # tighter top/bottom padding

      
  - block: collection
    id: news-list
    content:
      title: "Latest News"
      count: 2
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
      page_type: post
    design:
      view: compact
      columns: "1"
      spacing:
        padding: ['50px','0','40px','0']   # tighter top/bottom padding
      background:
        color: "transparent"
      css_style: "background-color: transparent;"
      css_class: "tight-news"            # we'll target this in CSS


  - block: markdown
    id: home-cta
    content:
      text: |-
        <div class="text-center">
          <a class="btn btn-primary btn-lg d-inline-flex align-items-center" href="/people/">
            <i class="fas fa-users" aria-hidden="true"></i>&nbsp;&nbsp;<span>Meet the team</span><span aria-hidden="true"> →</span>
          </a>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['45px','0','45px','0']   # tighter top/bottom padding




---
