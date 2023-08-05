---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact Us
      text: |-
        To contact us, please fill out the form below. We will get back to you as soon as possible.
      email: cecilia.ono@nyulmc.org
      phone: +1 212 777 7777
      address:
        street: East 30th Street
        city: New York
        region: NY
        postcode: '10016'
        country: United States
        country_code: US
      coordinates:
        latitude: '40.740780'
        longitude: '-73.973589'
      directions: Enter The Science Building from 30th Street and go to the 6th floor.
      office_hours:
        - 'Monday 09:00 to 17:00'
        - 'Tuesday 09:00 to 17:00'
        - 'Wednesday 10:00 to 17:00'
        - 'Thursday 09:00 to 17:00'
        - 'Friday 09:00 to 17:00'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA
          captcha: true
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
