---
title: Contact
sections:
  - section_id: contact_cta
    type: section_cta
    title: Call us at +91-9388477762
    # actions:
    #   - label: Contact us
    #     url: /contact
    #     style: primary
  - section_id: contact
    type: section_contact
    background: gray
    title: Contact
    content: >-
      Please feel free to send us a message. We'll get back to you soon.
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Name
        is_required: true
      - input_type: tel
        name: telephone
        label: Phone Number
        is_requrired: true
      - input_type: email 
        name: email
        label: Email (optional)
      # - input_type: select
      #   name: subject
      #   label: Subject
      #   default_value: Please select
      #   options:
      #     - Error on the site
      #     - Sponsorship
      #     - Other
      - input_type: textarea
        name: message
        label: Message
        is_required: true
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: landing
---
