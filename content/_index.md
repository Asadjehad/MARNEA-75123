---
title: "MARNEA Research Group"
date: 2022-10-24
type: landing

theme:
  primary_color: "#005f73"
  font: "Roboto"

sections:
  - block: hero
    content:
      title: "Welcome to MARNEA Research Group"
      subtitle: "Innovating Advanced Materials for Energy Applications"
      background:
        image: hero_energy.jpg
        text_color_light: true
    design:
      fullscreen: true
      overlay: true

  - block: markdown
    content:
      title: "MARNEA Research Group"
      image:
        filename: photo1.png
    design:
      image_fullscreen: true
      image_position: top

  - block: features
    content:
      title: "Key Research Areas"
      features:
        - title: "Energy Storage"
          description: "Innovative materials powering the future of batteries and supercapacitors."
          icon: battery
        - title: "Solar Energy"
          description: "Developing materials that enhance solar efficiency and sustainability."
          icon: sun
        - title: "Clean Energy Catalysis"
          description: "Driving hydrogen production and carbon capture with advanced catalysts."
          icon: flask
        - title: "Energy Conversion"
          description: "New materials for fuel cells, thermoelectrics, and calorics."
          icon: bolt
        - title: "Sustainable Materials"
          description: "Materials that are efficient, recyclable, and environmentally friendly."
          icon: leaf
        - title: "Smart & Nanomaterials"
          description: "Responsive and nanoscale materials transforming energy solutions."
          icon: atom
    design:
      columns: "3"

  - block: markdown
    content:
      title: "About MARNEA"
      text: |
        The **Advanced Materials Research Network for Energy Applications** is a collaborative group focused on the development of advanced materials, namely the synthesis, characterisation and theoretical understanding of functional materials able to be used in energy applications.

        The network promotes cooperation and dynamic exchange between researchers, improving efficiency and innovation across key areas in energy science.
    design:
      columns: "1"

  - block: collection
    content:
      title: "Latest News"
      count: 5
      filters:
        author: ""
        category: ""
        exclude_featured: false
        publication_type: ""
        tag: ""
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: "1"

  - block: markdown
    content:
      title: "Join Our Research Community"
      subtitle: "Explore collaboration opportunities and cutting-edge materials science"
      text: ""
    design:
      columns: "1"
      background:
        image:
          filename: coders.jpg
          filters:
            brightness: 0.6
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ["60px", "0", "60px", "0"]
      css_class: fullscreen

  - block: collection
    content:
      title: "Latest Preprints"
      count: 5
      filters:
        folders:
          - publication
        publication_type: "article"
    design:
      view: citation
      columns: "1"

  - block: markdown
    content:
      title: "Our Team"
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: "1"
