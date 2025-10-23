---
title: "MOFLab Projects"
date: 2025-10-20
type: landing

design:
  spacing: "5rem"

sections:

  - block: markdown
    content:
      #title: '<div style="grid-column: 1 / -1; text-align:left; font-size:1rem;">MOFLab projects</div>'
      text: |
        <p style="color:white; font-size:1.5rem;">MOFLab Projects: Exploring state-of-the-art optical fiber design and fabrication, low-cost and energy-efficient fiber sensors, and nonlinear fiber dynamics.</p>
    design:
      column: "1"
      background:
        color: "#163E82"
        image:
          filename: project.svg
          filters:
            brightness: 1
          position: left
          parallax: false
          size: cover
        padding: ["0px", "0px", "0px", "0px"]
        

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
