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
      captcha: true

  # Contact details (edit or remove options as required)
  email: jonathan.cr1302@gmail.com
  address:
    street:  Centre for Mathematical Sciences, Wilberforce Rd
    city: Cambridge
    region: CB
    postcode: 'CB3 0WA'
    country: United Kingdom
    country_code: UK
  directions: Pavilion G, Office G0.01

design:
  columns: '2'
---
