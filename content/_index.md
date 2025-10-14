---
# Leave the homepage title empty to use the site title
title:
date: 2025-10-12
type: landing
#header:
  #show_logo: true
  #logo:
    #image: "media/logo.jpg"
    #alt: "Research Group Logo"
    #height: 60

sections:

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: welcome.png
          filters:
            brightness: 1
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['2rem', '0', '2rem', '0']
      css_class: fullscreen
    
  - block: hero
    content:
      title: |
        Microstructure Optical Fiber Lab
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
      image:
        filename: welcome.png
        #parallax: false
        position: center
        size: cover
      design:
        columns: '1'
        spacing:
          padding: ['2rem', '0', '2rem', '0']
        text_align: left
        image_align: left
       css_class: fullscreen

      
      
  - block: collection
    content:
      title: Featured articles
      text: ""
      count: 10
      filters:
        folders:
          - publication
        publication_type: 'featured-article'
    design:
      view: citation
      columns: '1'
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
  


 
---
