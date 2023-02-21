---
date: "2023-02-13"
sections:
- block: v1/about
  content:
    text: null
    username: admin
  id: about
  design:
    background:
      image:
        filename: map_for_website.png
        darken: 1
        size: contain
        position: bottom
        parallax: false
        text_color_light: false
    spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["50px", "0px", "170px", "0px"]
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Working Papers
  design:
    columns: "2"
    view: card
  id: research
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - policy
    title: Policy Reports
  design:
    columns: "2"
    view: card
  id: policy
- block: contact
  content:
    address:
      city: 1015 Lausanne
      country: Switzerland
      country_code: CH
      postcode:
      region: Switzerland
      street: Office 508, Internef
    directions: Metro station UNIL-Chamberonne
    email: bernhard.nobauer@unil.ch
    subtitle: null
    text: Want to chat? Let's schedule a call or a meeting. Just send me an email!
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
