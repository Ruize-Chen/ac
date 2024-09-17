---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'About Research'
      subtitle: ''
      text: |1-
        I have background in sampling and measuring the environmental pollutants of both organic and inorganic matters, including PM2.5, SO2, NO2, COD, BOD, VOCs, toxic contaminations like POPs, endocrine disrupters, etc. Then I turned to simulating, analyzing, and evaluating the toxic organic contaminations through computational and statistical approaches during my graduate education. I employed various statistical analysis, such as FA, PCA, PMF, MLE, etc, and computational approaches like fugacity approach, ecotoxicological model, biogeochemical model, etc to understand, reveal, and solve environmental pollutant behavior, issues, and relevant public risks. We started to combine models and field measurements together in agriculture scope. I am also very interested in studying advanced approaches including ML, Bayesian Networks, Uncertainty (MCMC), etc, and Occam's razor. 

        Though my research background was strongly bone with environmental pollution, I was still seeking further research or educational opportunities in different scopes in ecological, environmental, marine, and agriculture-aquacultural fields. I am a doer and I do wish have chance to learn and conduct it.

        During my RA job, I am also in partnership of a tech company, that focuses on Digital Twins, XR tech, virtual interaction, CG presentation, meta, etc. I hope I can apply these approaches and ideas to scientific development, especially in environmental, ecological, marine, and agriculture-aquacultural fields in the future.


    design:
      columns: 1
  - block: collection
    id: publication
    content:
      title: Studies Gallery
      count: 4
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      count: 3
      filters:
        folders:
          - publication
        exclude_featured: false
        exclude_future: true
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]

        css_class: "bg-primary-700"
        css_style: ""
---
