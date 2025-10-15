---
# Leave the homepage title empty to use the site title
title:
date: 2025-10-12
type: landing

sections:
  - block: markdown
    content:
      title: Welcome to Microstructure Optical Fiber Lab
      subtitle: 
      text: |
        [Contact Us](../contact/){: .btn .btn-outline-light}
        

    design:
      columns: '1'
      background:
        color: "#7D8CBA"
        image: 
          filename: welcome.png
          filters:
            brightness: 1
          parallax: true
          position: center
          size: 45%
          text_color_light: true
        spacing:
        padding: ['0px', '0px', '0px', '0px']
      css_class: halfscreen

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
        We explore next-generation optical fiber technologies that transform how light travels. Our research focuses on groundbreaking hollow-core fibers with microscopic air channels that allow light to move faster,
        farther, and with remarkably low loss. By engineering advanced microstructured designs, we aim to achieve ultra-low transmission loss, low latency, broad bandwidth, and exceptionally low light–glass interaction—
        paving the way for the future of high-speed communication.
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
