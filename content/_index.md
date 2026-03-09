---
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 0.7
          size: cover
          position: center
          parallax: false

  - block: markdown
    id: publications
    content:
      title: Publications
      text: |-
        I have published several papers during my PhD journey.

        For the full and latest list of my publications, please visit my [Google Scholar profile](https://scholar.google.com/citations?user=Tif1W5AAAAAJ&hl=en).
    design:
      columns: '1'

  - block: collection
    content:
      title: Selected Projects
      text: Practical builds, experiments, and open-source work.
      filters:
        folders:
          - project
        exclude_featured: false
    design:
      view: article-grid
      columns: 3

  - block: collection
    id: news
    content:
      title: Latest Writing
      page_type: post
      count: 4
      filters:
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      offset: 0
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]
---
