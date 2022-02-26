---
layout: home
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/IMG_7961.jpg
    background_image_opacity: 65
    content: |
      # Baking sweets for every happy occasion!

      Say hello to EB!!!
    actions:
      - title: See all items
        url: /store
        arrow: true
        style: primary
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - content/category/bigplants.md
      - content/category/cactuses.md
  - type: testimonials_section
    section_id: testimonials_section
    title: Reviews
    testimonials:
      - author:
          name: John Dope
          location: 'Colorado, USA'
        text: >-
          I didn't know the Snipcart guys were into herbs as well! How beautiful
          is that Planty theme. I'm going to launch a killer JAMstack e-commerce
          store using this for sure.
      - author:
          name: Major Payne
          location: 'VA, USA'
        text: >-
          Well I'll be d*mned. These plants really ARE greener than any of my
          recruits.
  - type: promotion_section
    section_id: promotion_section
    title: Discover all the delicious sweets
    image: images/IMG_7897.jpg
    background_image: images/IMG_7950-1841bd7c.jpg
    cta:
      title: Discover
      url: /store
      style: secondary
      arrow: true
seo:
  title: Eb's Sweets
  description: The preview of the Planty theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Eb's Sweets
      keyName: property
    - name: 'og:description'
      value: The preview of the Planty theme
      keyName: property
    - name: 'og:image'
      value: images/header.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Eb's Sweets
    - name: 'twitter:description'
      value: The preview of the Planty theme
    - name: 'twitter:image'
      value: images/header.jpg
      relativeUrl: true
---
