---
title:
date: 2025-10-12
type: landing
design:
  spacing: "5rem"

sections:

  - block: markdown
    content:
      #title: '<div style="grid-column: 1 / -1; text-align:left; font-size:1rem;">MOFLab projects</div>'
      text: |
    design:
      column: "1"
      alignment:
        horizontal: center
        vertical: middle
      #css_class: fullscreen
      background:
        color: "#394B6E"
        image:
          filename: home_page_v1.svg
          filters:
            brightness: 1
          position: center
          parallax: false
          size: cover
            
      #padding: ['0px', '0', '0px', '0']
  
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

#<div id='header-text' style="height: 30vh">

#</div>


