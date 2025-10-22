---
title: "MOFLab Projects"
date: 2025-10-20
type: landing

design:
  spacing: "5rem"

sections:
  - block: hero
    content:
      title: '<div style="text-align: left;">MOFLab <span style="font-size: 2rem;">Projects</span></div>'
      text: '<p style="text-align:center; font-size:1.1rem;">Exploring optical fiber design, ultrafast photonics, and nonlinear fiber dynamics.</p>'
    design:
      columns: 1
      background:
        color: "#ffffff"

  - block: collection
    content:
      #title: '<div style="text-align:center;">MOFLab <span style="font-weight:300;">Projects</span></div>'
      #text: '<div style="text-align:left;">Exploring optical fiber design, ultrafast photonics, and nonlinear fiber dynamics.</div>'
      filters:
        folders:
          - projects
    design:
      view: showcase
      columns: 2
      background: 
        color: "#ffffff"
  
    sort_by: 'Date'
    sort_ascending: false
    cascade:
      show_breadcrumb: true
      show_related: true
      commentable: true

---
