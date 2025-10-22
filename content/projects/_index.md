---
title: "MOFLab Projects"
date: 2025-10-20
type: landing

design:
  spacing: "5rem"

sections:

  - block: hero
    content:
      #title: '<div style="grid-column: 1 / -1; text-align:left; font-size:1rem;">MOFLab projects</div>'
      text: text: 'Exploring state-of-the-art optical fiber design and fabrication, ultrafast photonics, and nonlinear fiber dynamics.'
    design:
      background:
        color: "white"

  - block: collection
    content:
      #title: '<div style="grid-column: 1 / -1; text-align:left; font-size:2rem;">MOFLab projects</div>'
      #text: '<div style="grid-column: 1 / -1; text-align:left; font-size:1.2rem;">Exploring optical fiber design, ultrafast photonics, and nonlinear fiber dynamics.</div>'
      filters:
        folders:
          - projects
    design:
      view: showcase
      columns: 2
      background: 
        color: "white"
  
    sort_by: 'Date'
    sort_ascending: false
    cascade:
      show_breadcrumb: true
      show_related: true
      commentable: true

---
