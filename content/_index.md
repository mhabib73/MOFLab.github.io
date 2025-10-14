---
# Leave the homepage title empty to use the site title
title:
date: 2025-10-12
type: landing

sections:
  - block: hero
    content:
      title: |
        Microstructure Optical Fiber Lab
      image:
        filename: welcome.png
      text: |
        <br>
        
        Dr. Habib is the director of Microstructure Optical Fiber Lab (MOFLab), where he leads cutting-edge research and innovation on next-generation optical fibers for photonics based applications.
        <br><br>
        Our research focuses on: <br>
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
