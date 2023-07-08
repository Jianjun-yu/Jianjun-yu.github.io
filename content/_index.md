---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.personal
    id: about
    content:
      title: 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: features
    id: research
    content:
      title: Research


  - block: collection
    content:
      title: Under Review
      filters:
        folders:
          - publication
        exclude_featured: true
        # under reviews are 2 , working papers are 3
        publication_type: "2"

        

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
        - title: American Political Science Association Annual Meeting & Exhibition
          company_logo: apsa
          description: |2-
            Spillover Racism: Explain Discrimination against Asian Americans, 2023

            Personality Cult or Performance? Chinese Strategies of Government Propaganda, with Shuyuan Shen, 2023
        - title: The Annual Meeting of the Political Methodology Society
          company_logo: polmeth
          description: |2-
            Poster: Large Language Model to Replace Human Labeling, with Rongxing Ouyang , 2023 
            
            Poster: Transformer-based Language Models for Text Clustering, 2023
            
            Poster: A Proper Topic Model for Short Text, 2022
        - title: The Annual Midwest Political Science Association Conference
          company_logo: mpsa
          description: |2-
            Signaling to Leaders not People: Understanding the Mechanics of Chinese Local Government Propaganda, 2023

            Personality Cult or Performance? Strategies of Local Government Propaganda in China, 2022
        - title: Broadening Our Approach, A Workshop on Comparative Political Communication. Duke University, Durham, NC, 2022
          description: How Do Chinese Local Governments Use Social Media to Communicate with their People?
    design:
      columns: '2'

  - block: collection
    content:
      title: Working paper
      filters:
        folders:
          - publication
        exclude_featured: true
        # under reviews are 2 , working papers are 3
        publication_type: "3"
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
          tag: 'wechat_spider'
        - name: Bibtransfer
          tag: 'bibtransfer'
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
          tag: 'wechat_data'
        - name: Twitter Data
          tag: 'twitter_data'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: experience
    id: teaching 
    content:
      title: Teaching experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Primary instructor course
          description: |2-
            Introduction to Public Opinion

            Online course: Introduction to Political psychology 

        - title: Teaching assistant
          description: |2-
            Political analysis
            
            Introduction to Comparative Politics
            
            Introduction to International Relation

            Introduction to American Foreign Policy

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: jianjyu@uiowa.edu
      phone: 508 410 0418
      address:
        street: 371 Schaeffer Hall
        city: Iowa city
        region: IA
        postcode: '52240'
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
    design:
      columns: '2'
---
