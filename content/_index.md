---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Wang's Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        **Department of Mechanics and Aerospace Engineering, Southern University of Science and Technology, Shenzhen, CHINA.**

        **南方科技大学力学与航空航天工程系**
  
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
      title: |
        Shell-based spinodal structure simulation by meshfree method
      subtitle:
      text: |
        {{< video src="spinodal.mp4" controls="yes" >}}
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']
      css_class: fullscreen



  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['40px', '0', '40px', '0']
  #     css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'


      
---