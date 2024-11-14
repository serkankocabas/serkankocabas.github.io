---
title: "Contact Page"
summary: "How to contact me"
type: landing

sections:
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: ''
      # Contact details - edit or remove options as needed
      email: skocabas@eco.uc3m.es
      address:
        street: Calle Madrid 126
        city: Getafe/Madrid
        postcode: '28903'
        country: Spain
        country_code: ES
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/serkankocabas26'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:serkan.kocabas'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://us05web.zoom.us/j/3089067331?pwd=WlBRbG9Qb3c4SDVJenZTeStzeFR5QT09'
      # Automatically link email and phone or display them just as text?
      autolink: true
      # Choose an email form provider (netlify/formspree)
      form:
        provider: netlify
        formspree:
          # If using Formspree, enter your Formspree form ID
          id: ''
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
      # Coordinates to display a map - set your map provider in `params.yaml`
      coordinates:
        latitude: '40.32039789444768'
        longitude: '-3.7172158565799847'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---