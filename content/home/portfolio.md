---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://docs.hugoblox.com/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: ''
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Modeling
      tag: Modeling
    - name: Fabrication
      tag: Fabrication
    - name: Sensor
      tag: Sensor

design:
  columns: '1'
  view: masonry
  flip_alt_rows: true
  background: {}
  spacing: {padding: [0, 0, 0, 0]}

sections:

  - block: markdown
    content:
      title: |
        <span style="font-size: 3rem; color: white; white-space: nowrap; text-align: left; display: block;">
        Welcome to Microstructure Optical Fiber Lab </span>
      
      text: |
        <span style="font-size: 2rem; color: white; white-space: nowrap; text-align: left; display: block;">
        advancing science of light for all </span>
        
    design:
      column: "1"
      alignment:
        horizontal: center
        vertical: middle
      background:
        color: ""
        image:
          filename: fiber_3D.png
          filters:
            brightness: 1
          position: center
          parallax: true
          size: cover
      css_class: hero-section 
      #spacing:
        #padding: ["0rem", 0, "0em", 0]
---
