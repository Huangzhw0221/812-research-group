---
# Leave the homepage title empty to use the site title
title:
date: 2023-11-20
type: landing

sections:
  - block: hero
    content:
      title: |
        ECUST-MMAI
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        The ECUST-MMAI Research Group is led by Professor Yu Zhu. The team is committed to the research of artificial intellegence, advanced deep learning algorithms, computer vision, and multimedia applications. Including Medical Imaging, Autonomous Driving, Deepfake, Image Superresolution, NERF, Expression Recognition and etc..

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
          filename: A_finalpic01.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
