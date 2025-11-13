---
title:
date: 2025-10-12
type: landing

#spacing: "0.5rem"


sections:

  - block: markdown
    content:
      title: |
        <br>
        <span style="font-size: 3rem; color: white; white-space: nowrap; text-align: left; display: block;">
        Welcome to Microstructure Optical Fiber Lab </span>
      
      text: |
        <span style="font-size: 2rem; color: white; white-space: nowrap; text-align: left; display: block;">
        advancing science of light for all </span>
        
    design:
      column: "1"
      alignment:
        horizontal: center
        vertical: middle
      background:
        color: ""
        image:
          filename: fiber_3D.png
          filters:
            brightness: 1
          position: center
          parallax: true
          size: cover
      #css_class: halfscreen
      spacing:
        padding: ["0rem", 0, "25em", 0]


  - block: markdown
    content:
      title: |
          
      text: |
        <div style="overflow: auto;">
        <figure src="HCARF_12tube_trans.gif" alt="Research visualization"
             style="float: left; margin: 0 20px 20px 0; width: 300px; height: 300px; border-radius: 20px;">
        <p>
        We investigate next-generation optical fiber technologies that redefine how light travels. Our work centers on innovative hollow-core fibers: engineered with microscopic air channels that let light propagate
        faster, over longer distances, and with exceptionally low loss. Through advanced microstructured designs, we aim to achieve ultra-low transmission loss, minimal latency, and broad bandwidth, opening new
        possibilities for the future of high-speed communication, data networks, and beyond.
        </p>

        <p>
        By combining theory, simulation, and experimental fabrication, we aim to understand the underlying physics of light propagation in complex fiber geometries. Our insights drive the development of practical fiber
        designs with transformative applications in AI data centers, quantum communication, ultrafast data transmission, advanced laser systems, fiber-optic sensing, and biomedical imaging.
        </p>

        <p>
        We welcome collaborations with academic groups, industry partners, and students interested in shaping the next generation of photonic technologies.
        </p>

        <p>
        Our research group focuses on:
        </p>

        <ul>
          <li>Advanced optical fiber design/modeling, fabrication, and characterization</li>
          <li>Smart, low-cost and energy-efficient fiber sensors</li>
          <li>Ultrafast nonlinear optics (single-mode and multi-mode regimes)</li>
          <li>Light-matter interactions</li>
          <li>Smart fiber-based nonlinear devices</li>
        </ul>
        </div>
    design:
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

        
    design:
      # Section background color (CSS class)
      css_class: "bg-primary-700"
      view: compact
      columns: '1'
      text_align: left
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]

  - block: portfolio
    content:
      title: '<div style="text-align: left; color: black;">Research areas</div>'
      text: ""
      count: 5
      filters:
        folders:
          - project
       
    design:
      view: masonry
      columns: '1'
      text_align: left
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]
  
  - block: collection
    content:
      title: '<div style="text-align: left; color: black;">Featured journal articles</div>'
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



---

