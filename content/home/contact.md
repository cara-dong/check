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
  email: caradong@berkeley.edu
  phone: 510 365 14 68

design:
  columns: '2'
  background:
    gradient_start: '#f7cac9'
    gradient_end: '#91a8d0'
    gradient_angle: 180
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true
  spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
    padding: ["20px", "0", "20px", "0"]
---
