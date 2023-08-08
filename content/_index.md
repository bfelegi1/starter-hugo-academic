---
# Leave the homepage title empty to use the site title
title: Home
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  
 
  - block: collection
    id: featured
    content:
      title: Working Papers
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: bfelegi@vt.edu
      phone: 561 598 98 93
      address:
        street: 3122 Pamplin Hall
        city: Blacksburg
        region: VA
        postcode: '24060'
        country: United States
        country_code: US
      office_hours:
        - 'Tuesdays 9:00 to 10:00am, 4:00 to 5:00pm'
        - 'Thursdays 9:00 to 10:00am, 4:00 to 5:00pm'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Twitter
          link: 'https://twitter.com/BFelegi'
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
