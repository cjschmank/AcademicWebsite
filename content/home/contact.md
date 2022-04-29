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
  email: christopher.schmank@cgu.edu
  phone: 
  address:
    street: 
    city: 
    region: 
    postcode: ''
    country: 
    country_code: 
  coordinates:
    latitude: ''
    longitude: ''
  directions: 
  office_hours:
  appointment_url: ''
  contact_links:
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
      link: https://github.com/cjschmank/'

design:
  columns: '2'
---
