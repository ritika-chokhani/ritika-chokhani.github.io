---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Current Projects
      text: Here are some of the projects I'm working on currently. 
      filters:
        folders:
         - projects
        tag: current
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false

  - block: collection
    content:
      title: Past Projects
      text: Here are some of the projects I've worked on in the past. 
      filters:
        folders:
         - projects
        tag: past
    design:
      view: article-grid
      fill_image: false
      columns: 1
      show_date: false
      show_read_time: false
      show_read_more: false
---
