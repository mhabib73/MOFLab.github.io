---
# Leave the homepage title empty to use the site title
title:
date: 2025-10-12
type: landing

sections:
  - block: markdown
    content:
      title: Welcome to Microstructure Optical Fiber Lab
      align: top
      subtitle: ''
      link:
        text: Join us
        url: ../contact/
        #align: right
    design:
      columns: '1'
      background:
        color: "#83B5E6"
        image: 
          filename: welcome.png
          filters:
            brightness: 1
          parallax: true
          position: center
          size: cover
          text_color_light: false
      spacing:
        padding: ['0px', '0px', '0px', '0px']
      overlay: true
      css_class: fullscreen
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
        The Microstructure Optical Fiber Lab conducts cutting-edge research on advanced fiber technologies that control and guide light in new ways. Our work focuses on microstructured, hollow-core, and anti-resonant
        optical fibers, which enable ultra-low-loss transmission, enhanced nonlinear performance, and precise optical sensing.
        <br>
        By combining theory, simulation, and experimental fabrication, we aim to understand the underlying physics of light propagation in complex fiber geometries and translate that knowledge into practical designs. Our
        research supports applications in quantum communication, high-speed data transmission, laser systems, and biomedical imaging.
        <br>
        We welcome collaborations with academic groups, industry partners, and students interested in shaping the next generation of photonic technologies.
        <br>
        Our research group focuses on: <br>
    
        * Advanced optical fiber design, fabrication, and characterization
        <br>
        * Energy-efficient and low-cost fiber sensors
        <br>
        * Ultrafast nonlinear optics
        <br>
        * Light-matter interactions
  
  - block: collection
    content:
      title: Featured articles
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

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

  

---
