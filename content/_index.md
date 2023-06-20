---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: features
    id: research
    content:
      title: Research

  - block: collection
    id: featured
    content:
      title: Writing Samples
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card  


  - block: collection
    content:
      title: Under Review
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  - block: experience
    content:
      title: Conference
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Large Language Model to Replace Human Labeling
          company: The Annual Meeting of the Political Methodology Society
          date_start: '2023-06-01'
          date_end: '2023-06-01'
          description: 
        - title: Transformer-based Language Models for Text Clustering
          company: The Annual Meeting of the Political Methodology Society
          date_start: '2023-06-01'
          date_end: '2023-06-01'
          description: 
        - title: Personality Cult or Performance---Strategies of Local Government Propaganda in China
          company: The Annual Midwest Political Science Association Conference
          date_start: '2022-04-04'
          date_end: '2020-04-04'
          description: 
        - title: Signaling to Leaders, not People---Understanding the Mechanics of Chinese Local Government Propaganda
          company: The Annual Midwest Political Science Association Conference
          date_start: '2023-04-04'
          date_end: '2023-04-04'
          description: 

        - title: A Proper Topic Model for Short Text
          company: The Annual Meeting of the Political Methodology Society 
          date_start: '2022-06-01'
          date_end: '2022-06-02'
          description:            
        - title: Personality Cult or Performance---Strategies of Local Government Propaganda in China
          company: The Annual Midwest Political Science Association Conference
          date_start: '2022-04-04'
          date_end: '2020-04-04'
          description: 
        - title: How Do Chinese Local Governments Use Social Media to Communicate with their People?
          company: Broadening Our Approach, A Workshop on Comparative Political Communication
          date_start: '2022-03-01'
          date_end: '2020-03-01'
          description:
    design:
      columns: '2'

  - block: collection
    content:
      title: Working paper
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  - block: portfolio
    id: software
    content:
      title: Software
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: Wechat spider
          tag: 'Wechat spider'
        - name: Twitter spider
          tag: 'Twitter spider'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: portfolio
    id: data
    content:
      title: Data
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: Wechat Data
          tag: 'Wechat spider'
        - name: Twitter Data
          tag: 'Twitter spider'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: test@example.org
      phone: 888 888 88 88
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
