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
  email: icli@ucdavis.edu
  phone: 530 979 3284
  address:
    street: 2064 Kemper Hall, 1 Shield Ave.
    city: Davis
    region: CA
    postcode: '95616'
    country: United States
    country_code: US
  coordinates:
    latitude: '38.5449'
    longitude: '-122.740517'
  directions: Enter Kemper Hall and take the stairs to Office on Floor 3
  office_hours:
    - 'by Appointment'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
