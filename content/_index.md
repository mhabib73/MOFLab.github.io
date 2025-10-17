---
# Leave the homepage title empty to use the site title
title: 'MOFLab'
date: 2025-10-12
type: landing

sections:
  - block: markdown
    content:
      title: '<div style="text-align: right; color: white;">Microstructure Optical Fiber Lab</div>'
            
      subtitle: |
        
      
      text: |

    design:
      columns: '1'
      background:
        color: '#394B6E'
        #gradient_start: '#4bb4e3'
        #gradient_end: '#2b94c3'
        #gradient_angle: 180
        #text_color_light: true
        image: 
          filename: welcome.svg
          filters:
            brightness: 1
          parallax: true
          position: left
          parallax: false
          size: 70%
          text_color_light: false
        spacing:
        padding: ['10px', '0', '0', '0']
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
