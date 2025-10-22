---
title: "MOFLab Projects"
date: 2025-10-20
type: landing

design:
  spacing: "5rem"

sections:
  #- block: hero
    #content:
      #title: "MOFLab Projects"
      #text: "Exploring optical fiber design, ultrafast photonics, and nonlinear fiber dynamics."
    #design:
      #background:
        #color: "#ffffff"

  - block: collection
    content:
      title: '<div style="text-align:center;">MOFLab <span style="font-weight:300;">Projects</span></div>'
      text: '<div style="text-align:left;">Exploring optical fiber design, ultrafast photonics, and nonlinear fiber dynamics.</div>'
      filters:
        folders:
          - projects
    design:
      view: showcase
      columns: 2
  
    sort_by: 'Date'
    sort_ascending: false
    cascade:
      show_breadcrumb: true
      show_related: true
      commentable: true

---
