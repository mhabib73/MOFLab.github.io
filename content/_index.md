---
title:
date: 2025-10-12
type: landing

sections:
  - block: hero
    
    content:
      title: '<div style="text-align: right; color: cyan;">Microstructure Optical Fiber Lab</div>'
    design:
      columns: "1"
      background:
        color: "#394B6E"
        image:
          filename: welcome.svg
          filters:
            brightness: 1
          position: left
          parallax: false
          size: contain
        padding: ["0px", "0px", "0px", "0px"]
      #css_class: fullscreen


  - block: markdown
    content:
      title: |
        
      #image:
        #filename: welcome.png
        #filters:
          #brightness: 1
        #position: center
        #size: cover
      text: |
        <br>
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

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - projects
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
      - name: All
        tag: '*'
      - name: Programming
        tag: Programming
      - name: Web Development
        tag: Web Development
      - name: Software Engineering
        tag: Software Engineering
      - name: Machine Learning
        tag: Machine Learning
      - name: Deep Learning
        tag: Deep Learning
      - name: Natural Language Processing
        tag: Natural Language Processing
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  
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

---

