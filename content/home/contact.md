---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact
activate: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

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
  
design:
  columns: '2'
  spacing:
    padding: ["80px", "0", "60px", "0"]
---
