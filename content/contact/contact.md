---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10
  title: contact
subtitle:

content:
  # Contact (edit or remove options as required)
  email: test@example.org
  appointment_url: 'https://calendly.com'
  contact_links:
  - icon: comments
    icon_pack: fas
    name: Discuss on the forum
    link: 'https://github.com/wowchemy/wowchemy-hugo-themes/discussions'

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
  columns: '1'
---

Test page. Put info in
