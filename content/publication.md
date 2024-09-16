---
title: Publications
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    id : publication
    content:
      title: Selected Studies
      count: 6
      text: ""
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: article-grid
      columns: 3
  - block: collection
    content:
      title: Peer-reviewed Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
        exclude_future: true
    design:
      view: citation
---
