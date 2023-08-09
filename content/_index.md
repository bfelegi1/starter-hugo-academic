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
  - block: portfolio
    id: projects
    content:
      title: Working Papers
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Research in Progress
      filters:
        folders:
          - progress
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: experience
    id: teaching
    content:
      title: Teaching
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Instructor of Record 
          company: Virginia Tech
          company_url: 'https://www.vt.edu/'
          company_logo: Virginia_Tech_Hokies_logo
          location: Blacksburg, VA
          date_start: '2023-08-01'
          date_end: ''
          description: Analysis of Economic Data (Fall 2023)
        - title: Instructor of Record
          company: University of Notre Dame
          company_url: 'https://www.nd.edu/'
          company_logo: Notre_Dame_Fighting_Irish_logo
          location: Notre Dame, IN
          date_start: '2022-06-01'
          date_end: '2022-12-31'
          description: |2-
              Classes Taught:
              * Statistics for Economics Tutorial
              * Principles of Microeconomics
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to contact me with any questions!
      # Contact (add or remove contact options as necessary)
      email: bfelegi@vt.edu
      phone: +1 (561) 598-9893
      address:
        street: 3122 Pamplin Hall
        city: Blacksburg
        region: VA
        postcode: '24060'
        country: United States
        country_code: US
      office_hours:
        - 'Tuesdays 9:00 to 10:00am and 4:00 to 5:00pm'
        - 'Thursdays 9:00 to 10:00am and 4:00 to 5:00pm'
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
