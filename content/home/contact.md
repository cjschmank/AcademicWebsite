---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: chris.schmank@health.slu.edu
  phone: 314-977-7299
  address:
    street: 3700 Lindell Blvd., Morrissey Hall
    city: St. Louis
    region: 
    postcode: '63108'
    country: 
    country_code: 
  coordinates:
    latitude: ''
    longitude: ''
  directions: 
  office_hours:
  appointment_url: ''
  contact_links:
    - icon: calendar-plus
      icon_pack: fa
      name: 'Schedule an Appointment'
      link: 'https://calendly.com/christopher-j-schmank'
    - icon: "butterfly"
      icon_pack: "emoji"
      name: Follow on Blue Sky
      link: 'https://bsky.app/profile/cjschmank.bsky.social/'
    - icon: twitter
      icon_pack: fab
      name: Follow on Twitter
      link: 'https://twitter.com/cjschmank'
    - icon: linkedin
      icon_pack: fab
      name: Find on LinkedIn
      link: 'https://www.linkedin.com/in/christopherjschmank/'
    - icon: osf
      icon_pack: ai
      name: Find on OSF
      link: 'https://osf.io/b57sp/'
    - icon: researchgate
      icon_pack: fab
      name: Find on ResearchGate
      link: https://www.researchgate.net/profile/Christopher-Schmank-2'    
    - icon: google-scholar
      icon_pack: ai
      name: Find on GoogleScholar
      link: 'https://scholar.google.com/citations?user=-C3eiuYAAAAJ&hl=en'
    - icon: github
      icon_pack: fab
      name: Find on GitHub
      link: https://github.com/cjschmank'

design:
  columns: '2'
---
