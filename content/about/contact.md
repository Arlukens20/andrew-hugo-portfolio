---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Get in touch
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

  email: arlukens20@gmail.com
  phone: 317-775-2265
  appointment_url: 'https://calendly.com/arlukens/30min'
  #   address:
  #     street: 1150 Spruce Street
  #     city: Indianapolis
  #     region: IN
  #     postcode: '46203'
  #     country: United States
  #     country_code: US
  # coordinates:
  #   latitude: '37.4275'
  #   longitude: '-122.1697'
  # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  # office_hours:
  #   - 'Monday 10:00 to 13:00'
  #   - 'Wednesday 09:00 to 10:00'
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: link in
      link: 'www.linkedin.com/in/andrewlukens'
    - icon: github
      icon_pack: fab
      name: git
      link: 'https://github.com/Arlukens20'

design:
  columns: '1'
---
