---
title: Publication
date: 2023-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Studies
      count: 4
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
      count: 4
      filters:
        folders:
          - publication
        exclude_featured: false
        exclude_future: true
    design:
      view: citation

---
