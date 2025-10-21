---
title: 'Projects'
date: 2025-10-20
type: landing

design:
  # Section spacing
  spacing: '3rem'

# Page sections
sections:
  # Hero section at top
  - block: hero
    content:
      title: "MOFLab Projects"
      text: "Explore our research group's innovative projects"
    design:
      background:
        color: 'primary'
  
  # Projects grid below
  - block: collection
    content:
      #title: "Featured Projects"
      #text: "Here are a selection of projects that our research group are currently working on."
      filters:
        folders:
          - projects
    design:
      background:
        color: 'primary'
      view: article-grid
      columns: 2
      show_description: false
      show_date: false
      show_read_time: false
      show_read_more: false
      show_date: false

---
