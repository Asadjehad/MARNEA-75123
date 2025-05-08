---
title: ""
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: ""
    
  - block: markdown
    content:
      title: "MARNEA Research Group"
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

        **Some key 

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
