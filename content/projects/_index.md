---
title: 'Projects'
date: 2024-05-19
type: landing

cascade:
  - target:
      path: '{/projects/**}'
    params:
      show_date: false

# Page sections
sections:
  - block: collection
    content:
      title: Selected Projects
      text: Projects, tools, and pipelines from my research - built to probe, analyze, and secure large language models.
      filters:
        folders:
          - projects
        featured_only: false
      count: 0
    design:
      view: card
      fill_image: false
      columns: 1
      show_date: false
      show_read_time: false
      show_read_more: true
---
