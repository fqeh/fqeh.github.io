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
    id: contact
    content:
      title: Connect
      text: |-
        Find my publications on [Google Scholar](https://scholar.google.com/citations?user=Tif1W5AAAAAJ&hl=en), connect on [LinkedIn](https://www.linkedin.com/in/ali-alfageeh-182755132/), or visit the [Amin Alipour Lab](https://www.aminalipour.com/team).
    design:
      columns: '1'

  - block: collection
    content:
      title: Recent Publications
      page_type: publication
      count: 5
      order: desc
    design:
      view: citation
      columns: 1
---
