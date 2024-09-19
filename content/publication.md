---
title: 'publication'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

sections:
  - block: collection
    id: papers
    content:
      title: Featured Publications
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
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
