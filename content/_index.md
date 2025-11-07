---
title:
date: 2025-10-12
type: landing

spacing: "1rem"

sections:
    
  - block: markdown
    #content:
      #title: '<div style="grid-column: 1 / -1; text-align:left; font-size:1rem;">MOFLab projects</div>'
      #text: |
    design:
      column: "1"
      alignment:
        horizontal: center
        vertical: middle

      css_class: "bg-gray-100 dark:bg-gray-800"
      background:
        color: "#36454F"
        image:
          filename: home_page_v5.svg
          filters:
            brightness: 1
          position: center
          parallax: false
          size: contain
      css_class: min-h-screen
    content:
      title: |       
      text: |  
        <br>
        <br>
        <br>
      #padding: ['0px', '0', '0px', '0']

  - block: hero
    content:
      title: Write Docs Fast, Focus on Your Content
      text: The easy, no-code technical documentation solution your users will love 🎉
      primary_action:
        text: Get Started
        url: https://hugoblox.com/templates/details/docs/
        icon: rocket-launch
      secondary_action:
        text: Read the docs
        url: /docs/
      announcement:
        text: "Announcing the release of version 2."
        link:
          text: "Read more"
          url: ""
    design:
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      #css_class: min-h-screen
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: home_page_v5.svg
          filters:
            brightness: 1


  - block: markdown
    content:
      title: Welcome to Microstructure Optical Fiber Lab 
          
      text: |
        We investigate next-generation optical fiber technologies that redefine how light travels. Our work centers on innovative hollow-core fibers—engineered with microscopic air channels that let light propagate faster,
        over longer distances, and with exceptionally low loss. Through advanced microstructured designs, we aim to achieve ultra-low transmission loss, minimal latency, and broad bandwidth, opening new possibilities for
        the future of high-speed communication, data networks, and beyond.
        <br><br>
        By combining theory, simulation, and experimental fabrication, we aim to understand the underlying physics of light propagation in complex fiber geometries. Our insights drive the development of practical fiber
        designs with transformative applications in AI data centers, quantum communication, ultrafast data transmission, advanced laser systems, fiber-optic sensing, and biomedical imaging.
        <br><br>
        We welcome collaborations with academic groups, industry partners, and students interested in shaping the next generation of photonic technologies.
        <br><br>
        Our research group focuses on: <br>
    
        * Advanced optical fiber design, fabrication, and characterization
        <br>
        * Energy-efficient and low-cost fiber sensors
        <br>
        * Ultrafast nonlinear optics
        <br>
        * Light-matter interactions
        <br>
        * Smart fiber-based nonlinear devices
    design:
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]

  - block: collection
    content:
      title: '<div style="text-align: left; color: black;">Research areas</div>'
      text: ""
      count: 5
      filters:
        folders:
          - research
        #publication_type: 'featured-article'
    design:
      view: showcase
      columns: '1'
      text_align: left
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]
  
  - block: collection
    content:
      title: '<div style="text-align: left; color: black;">Featured articles</div>'
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'featured-article'
    design:
      view: citation
      columns: '1'
      text_align: left
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]


  - block: collection
    content:
      title: '<div style="text-align: left; color: black;">Latest news</div>'
      text: ""
      count: 5
      filters:
        folders:
          - news
        #publication_type: 'featured-article'
    design:
      # Section background color (CSS class)
      css_class: "bg-primary-700"
      #view: list
      columns: '1'
      text_align: left
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]


---
