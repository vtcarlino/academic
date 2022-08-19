---
widget: pages
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (title etc.) ...
title: Actualités
subtitle: ''

# Position of this section on the page
weight: 30

content:
  # Filter content to display
  filters:
    # The folders to display content from
    folders:
      - post
    tag: ''
    category: 'aac'
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 10
  # Choose how many pages you would like to offset by
  # Useful if you wish to show the first item in the Featured widget
  offset: 0
  # Field to sort by, such as Date or Title
  sort_by: 'Date'
  sort_ascending: false
design:
  # Choose a listing view
  view: compact
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
---
