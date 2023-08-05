---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        The
        
        Goldberg Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The Goldberg Laboratory explores lipid transportation pathways, utilizing innovative models like the first LpL floxed mice and others with altered heart lipid metabolism, to understand heart metabolism, lipotoxicity, and the unique challenges in atherosclerosis repair in mouse models.

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: nyu-science-building.jpg
          filters:
            brightness: 1
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: nyu-science-building.jpg
          filters:
            brightness: 1
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
#  - block: markdown
#    content:
#      title:
#      subtitle:
#      text: |
#        {{ % cta cta_link="./people/" cta_text="Meet the team →" % }}
#    design:
#      columns: '1'
---