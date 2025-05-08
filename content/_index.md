---
title: ""
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: ""
      image:
        filename: photo1.png  
    design:
      image_fullscreen: true
      image_position: top

  - block: markdown
    content:
      title: "MARNEA Research Group"
      text: |
        The **Advanced Materials Research Network for Energy Applications** is a collaborative group focused on the development of advanced materials, namely the synthesis, characterisation and theoretical understanding of functional materials able to be used in energy applications. The network essentially aims to promote cooperation and create a dynamic of exchange between the involved researchers. The pooling of knowledge and know-how through this exchange network will allow the different actors to improve their efficiency, whether in solving technical problems in the development of materials or in the development of new technological applications.

        **Some key areas of interest within networking:**

        - **Energy Storage**: Development of advanced materials for energy storage systems.
        - **Solar Energy**: Research into new materials for solar cells that can increase efficiency, lower costs, and enhance the scalability of solar energy technology.
        - **Catalysis for Clean Energy**: Advanced materials used in catalysis for processes like hydrogen production, CO₂ capture, and conversion of biofuels.
        - **Materials for Energy Conversion**: Development of new materials for electrocaloric, magnetocaloric, fuel cells, microbial fuel cells, thermoelectrics, etc.
        - **Sustainable Materials**: Materials that are not only efficient but also sustainable, addressing issues like raw material sourcing, recyclability, and minimizing environmental impact.
        - **Nanomaterials and Nanotechnology**: These materials can offer significant improvements in energy-related applications due to their unique properties at the nanoscale, such as increased surface area, better conductivity, or enhanced chemical reactivity.
        - **Smart Materials**: Materials that can dynamically change in response to environmental conditions, enabling energy savings or more efficient use of energy.
        - **Theory and Simulation of Materials**.
    design:
      columns: "1"
      spacing:
        padding: ["20px", "20px", "20px", "20px"]

  - block: collection
    content:
      title: "Latest News"
      subtitle: ""
      text: ""
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
      title: ""
      subtitle: ""
      text: ""
    design:
      columns: "1"
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ["20px", "0", "20px", "0"]
      css_class: fullscreen

  - block: collection
    content:
      title: "Latest Preprints"
      text: ""
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
      title: ""
      subtitle: ""
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: "1"
---
