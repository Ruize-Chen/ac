---
title: Publications
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '6rem'

# Page sections
sections:
  - block: collection
    id: publication
    content:
      title: Studies
      count: 4
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      count: 4
      filters:
        folders:
          - publication
        exclude_featured: false
        exclude_future: true
    design:
      view: citation
---
