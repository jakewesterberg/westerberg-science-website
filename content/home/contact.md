---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 100

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
      captcha: true

  # Contact details (edit or remove options as required)
  email: jacob.a.westerberg@vanderbilt.edu
  address:
    street: 111 21st Avenue South
    city: Nashville
    region: TN
    postcode: '37240'
    country: United States
    country_code: US

design:
  columns: '2'
---
