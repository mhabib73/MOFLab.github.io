---
# Leave the homepage title empty to use the site title
title:
date: 2025-10-12
type: landing

sections:
  - block: hero
    content:
      title: |
      text: |
      image:
        filename: welcome.png
        #parallax: false
        position: left
        size: cover
  - block: markdown
    content:
      title: 
    
      text: |
        Dr. Habib is the director of Microstructured Fiber Photonics Lab (MFPL), where he leads cutting-edge research and innovation on next-generation optical fibers for photonics based applications.
        <br><br>
        Our research focuses on: <br>
        * Advanced optical fiber design, fabrication, and characterization
        <br>
        * Energy-efficient and low-cost fiber sensors
        <br>
        * Ultrafast nonlinear optics
        <br>
        * Light-matter interactions
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        Dr. Habib is the director of Microstructured Fiber Photonics Lab (MFPL), where he leads cutting-edge research and innovation on next-generation optical fibers for photonics based applications.
        <br><br>
        Our research focuses on: <br>
        * Advanced optical fiber design, fabrication, and characterization
        <br>
        * Energy-efficient and low-cost fiber sensors
        <br>
        * Ultrafast nonlinear optics
        <br>
        * Light-matter interactions
    design:
      columns: '1'
      background:
        image: 
          filename: welcome.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: collection
    content:
      title: Latest articles
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'
  


 
---
