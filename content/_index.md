---
# Leave the homepage title empty to use the site title
title:
date: 2025-10-12
type: landing

sections:
  - block: hero
    content:
      title: |
        Next-generation Optical Fiber Lab (NOFLab)
      image:
        filename: welcome.png
      text: |
        <br>
        
        Dr. Habib is the director of Next-generation Optical Fiber Lab (NOFLab), where he leads cutting-edge research and innovation on next-generation optical fibers for photonics based applications.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'journal'
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
