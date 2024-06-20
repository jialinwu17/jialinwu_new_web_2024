---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-02-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: collection
    content:
      title: Selected Publications
      text: Please see my google scholar for full publications and preprints.
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Scientist
          company: Google Deepmind
          company_url: 'https://deepmind.google/'
          location: Los Angelos
          date_start: '2022-08-29'
        - title: Research Intern
          company: Allen Institute for AI
          company_url: 'https://allenai.org'
          location: Seattle
          date_start: '2020-05-01'
          date_end: '2020-08-01'
        - title: Research Intern
          company: Google Inc.
          company_url: 'https://research.google/'
          location: New York City
          date_start: '2019-05-01'
          date_end: '2019-08-01'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: jialinwu@google.com
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
    design:
      columns: '2'
---
