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
  email: cta697140@mail.ustc.edu.cn
  phone: +86 17718471030
  address:
    street: 443 Huangshan Road, Shushan District
    city: Hefei
    region: Anhui Province
    postcode: '230027'
    country: China
    country_code: CN
  coordinates:
    latitude: '31.8467'
    longitude: '117.2652'
  directions: Enter the East Building of Laboratory Edifice and take the elevator to Office 417 on the floor 4
  office_hours:
    - 'Friday 9:00 to 11:00'
    - 'Saturday 14:00 to 17:00'
 # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: reseachgate
      icon_pack: fab
      name: Communicating through Reseachgate
      link: 'https://www.researchgate.net/profile/Tianao-Chen-2'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
