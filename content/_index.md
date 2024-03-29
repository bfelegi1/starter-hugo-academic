---
# Leave the homepage title empty to use the site title
title: 
date: 2024-10-24
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
  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - teaching
        exclude_featured: true
    design:
      columns: '2'
      view: card
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to contact me with any questions!
      # Contact (add or remove contact options as necessary)
      email: bfelegi@vt.edu
      phone: +1 (540) 231-4431
      address:
        street: 3122 Pamplin Hall
        city: Blacksburg
        region: VA
        postcode: '24060'
        country: United States
        country_code: US
      office_hours:
        - 'By Appointment'
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
