---
title: Publications
cms_exclude: true

design:
  # Section spacing
  spacing: '5rem'

sections:
  - block: collection
    id: publication
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
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

# View.
view: citation

# Optional header image (relative to `static/media/` folder).
---
