---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: 70%
          icon: r-project
          icon_pack: fab
        - name: Epidemiology
          description: 20%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Reseach Fellow
          company: University of Tasmania
          company_url: ''
          company_logo: utas
          location: lutruwita/Tasmania
          date_start: '2019-09-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Co-ordination of two longitudinal epidemiological trials
              * Preparation of grants/manuscripts
              * Research management
        - title: Epidemiologist
          company: Department of Health
          company_url: ''
          company_logo: doh
          location: lutruwita/Tasmania
          date_start: '2021-11-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * COVID-19 analysis of genomics, vaccination status, hospitalisations
              * Preparation of internal/external reports
              * Data analysis
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-

      # Contact (add or remove contact options as necessary)
      email: eddy.roccati@utas.edu.au
      phone: 03 6226 4228 
      appointment_url: ''
      address:
        street: 17 Liverpool St
        city: Hobart
        region: Tasmania
        postcode: '7000'
        country: Australia
        country_code: AUS
      directions:
      office_hours:
        - 'Weekdays 8:30 to 16:30'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/eddy_roccati'
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
