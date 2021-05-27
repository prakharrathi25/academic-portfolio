---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Intern
    company: National Institute for Research in Digital Science and Technology (INRIA)
    company_url: 'https://www.inria.fr/en'
    company_logo:
    location: Lille, France
    date_start: '2021-03-06'
    date_end: '2021-06-01'
    description: |2-
    
        * Worked with the highest ranked research institute in France on a problem of suicide analysis in Lille.
        * Used the socio-economic data collected from people who attempted suicide to predict whether they would attempt it again. It was also used to identify the factors which contribute to first time and repeated attempts.
        * Implemented the concepts of semi-parametric regression, statistical modelling and spatial econometrics using R.   
        * Our work determined the probablity of suicide attempts in the next 6 months with an AUC Score of 0.89. This work will be submitted to the local government in Lille and a paper will also be written.
        
  - title: Professor of Semiconductor Physics
    company: University X
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---
