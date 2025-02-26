---
# Leave the homepage title empty to use the site title
title: multi-media
date: 2022-10-24
type: landing

sections:





  - block: markdown
    content:
      title: |
        A twisted soda can by RKPM meshfree method
      subtitle:
      text: |
        {{< video src="soda.mp4" controls="yes" >}}
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']
      css_class: fullscreen

  - block: markdown
    content:
      title: |
        Shell-based spinodal structure by RKPM meshfree method
      subtitle:
      text: |
        {{< video src="spin.mp4" controls="yes" >}}
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