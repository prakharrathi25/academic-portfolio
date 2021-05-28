---
title: "My Projects"  # Add a page title.
summary: "Hello!"  # Add a page description.
date: "2019-01-01T00:00:00Z"  # Add today's date.
# type: "widget_page"  # Page type is a Widget Page

# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 65

title: Projects
subtitle: 'Some of the things I have built in the past'

content:
  # Page type to display. E.g. project.
  page_type: allprojects

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
  - name: Deep Learning
    tag: Deep Learning
  - name: Natural Language Processing
    tag: nlp
  - name: Data Science
    tag: Data Science
  - name: Tools and Applications
    tag: apps

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '3'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 5

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---

---

