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
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['10px', '0', '10px', '0']
      css_class: halfscreen
  - block: hero
    content:
      title: |
        Microstructure Optical Fiber Lab
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
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
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
