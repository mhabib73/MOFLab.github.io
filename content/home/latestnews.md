---
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

  - block: collection
    content:
      title: '<div style="text-align: left; color: black;">Latest news</div>'
      text: ""
      count: 5
      filters:
        folders:
          - news

        
    design:
      # Section background color (CSS class)
      css_class: "bg-primary-700"
      view: compact
      columns: '1'
      text_align: left
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]
---
