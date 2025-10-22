---
widget: collection
title: Selected Projects
cms_exclude: true

# Optional header image (relative to `static/media/` folder).
header:
  caption: ""
  image: ""

view: detailed

weight: 10

content:
  # Filter content to display
  filters:
    # The folders to display content from
    folders:
      - projects
    featured_only: false
    exclude_featured: false
    exclude_future: false
    exclude_past: false
#    tag: ''
#    category: ''
#    publication_type: ''
#    author: ''
  # Choose how many pages you would like to display (0 = all pages)
  count: 0
  # Choose how many pages you would like to offset by
  # Useful if you wish to show the first item in the Featured widget
  offset: 0
  # Field to sort by, such as Date or Title
  sort_by: 'Date'
  sort_ascending: false

cascade:
  show_breadcrumb: true
  show_related: true
  commentable: true
---
