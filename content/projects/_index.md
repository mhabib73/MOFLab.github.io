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
      text: 
    design:
      column: "1"
      background:
        color: "#103B5C"
        image:
          filename: project.svg
          filters:
            brightness: 1
          position: center
          parallax: false
          size: 70%
          #padding: ['0px', '0', '0px', '0']
        
      #spacing:
        #padding: ['20px', '0', '20px', '0']
        

  - block: collection
    content:
      #title: '<div style="grid-column: 1 / -1; text-align:left; font-size:2rem;">MOFLab projects</div>'
      text: |
        <p style="color:black; font-size:1.5rem;">MOFLab Projects: Exploring state-of-the-art optical fiber design and fabrication, low-cost and energy-efficient fiber sensors, and nonlinear fiber dynamics.</p>
        <br><br>
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
