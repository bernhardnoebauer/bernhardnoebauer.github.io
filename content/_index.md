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
      padding: ["52px", "0px", "170px", "0px"]
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
      publication_type: "3"
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
      - publication
      publication_type: "4"
    title: Policy Reports
  design:
    columns: "2"
    view: card
  id: policy
- block: markdown
  content:
    title: Teaching
    text: I was fortunate to teach Development Economics in the 2022/23 fall semester together with [Dzhamilya Nigmatulina](https://sites.google.com/view/dzhamilyanigmatulina/home) and [Resuf Ahmed](https://resuf.github.io/). <br /> <br />Here you can find the [syllabus](https://hecnet.unil.ch/hec/syllabus/descriptif/2788) and the [course website](https://moodle.unil.ch/course/view.php?id=25187). <br /> <br />And here you can find {{< staticref "uploads/Introduction_to_QGIS_Week_1.pdf" >}}part 1{{< /staticref >}} and {{< staticref "uploads/Introduction_to_QGIS_Week_2.pdf" >}}part 2{{< /staticref >}} of the short introduction to [QGIS](https://www.qgis.org/en/site/) that I put together. For more involved spatial operations check out the [sf](https://cran.r-project.org/web/packages/sf/index.html) package in [R](https://www.r-project.org/).
  design:
    columns: '2' 
  id: teaching
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
