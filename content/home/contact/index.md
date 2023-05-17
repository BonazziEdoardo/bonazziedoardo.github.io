---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Say hi 👋
subtitle: Feel free to contact me :)

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: 
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  # email: edoardo.bonazzi.2001@gmail.com
  # appointment_url: 'https://calendly.com/edoardo-debenedetti/30min'
  contact_links:
    - icon: envelope
      icon_pack: fas
      name: edoardo.bonazzi.2001@gmail.com 
      link: 'mailto:edoardo.bonazzi.2001@gmail.com'
design:
  columns: '2'
---