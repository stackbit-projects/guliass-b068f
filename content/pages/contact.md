---
title: Get in Touch
img_path: images/contact.jpg
form_id: contactForm
form_action: /success
form_fields:
  - input_type: text
    name: name
    label: Name
    is_required: true
    default_value: Юлия
  - input_type: email
    name: email
    label: Email
    default_value: pa-op@mail.ru
    is_required: true
  - input_type: select
    name: julia18042
    label: Subject
    default_value: Please select
    options:
      - Error on the site
      - Sponsorship
      - Other
  - input_type: textarea
    name: message
    label: Message
    default_value: Привет! Рада видеть тебя на своем новом сайте!
  - input_type: checkbox
    name: consent
    label: >-
      I understand that this form is storing my submitted information so I can
      be contacted.
submit_label: Send Message
seo:
  title: Get in Touch
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Get in Touch
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'og:image'
      value: images/contact.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Get in Touch
    - name: 'twitter:description'
      value: This is the contact page
    - name: 'twitter:image'
      value: images/contact.jpg
      relativeUrl: true
layout: contact
---
### To get in touch fill the form below.
