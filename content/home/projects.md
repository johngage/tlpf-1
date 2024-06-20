---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
menu:
  main:
    name: "Projects"
    weight: 1
    identifier: "projects"
    
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 25

title: Projects
subtitle: 'Athletic Training and Educational Sites'

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Athletic Training
      tag: 'training'
    - name: School
      tag: 'school'
    - name: Refugee Camp
      tag: 'camp'
    - name: Peace Race
      tag: 'race'

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card 
  #   5 = Showcase
  view: 3
  background:
    color: "#00b300"


  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
