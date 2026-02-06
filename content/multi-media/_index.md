---
# Leave the homepage title empty to use the site title
title: multi-media
date: 2022-10-24
type: landing

sections:

  - block: markdown
    content:
      title: |
        Landslide by RKPM meshfree method
      subtitle:
      text: |
        {{< video src="landslide.mp4" poster="multi-media-posters/landslide.png" controls="yes" >}}
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']
      css_class: video-narrow

  - block: markdown
    content:
      title: |
        Penetration by RKPM meshfree method
      subtitle:
      text: |
        {{< video src="penetration.mp4" poster="multi-media-posters/penetration.png" controls="yes" >}}
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']
      css_class: video-narrow

  - block: markdown
    content:
      title: |
        A twisted soda can by RKPM meshfree method
      subtitle:
      text: |
        {{< video src="soda.mp4" poster="multi-media-posters/soda.png" controls="yes" >}}
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']
      css_class: video-narrow

  - block: markdown
    content:
      title: |
        Shell-based spinodal structure by RKPM meshfree method
      subtitle:
      text: |
        {{< video src="spin.mp4" poster="multi-media-posters/spinodal.png" controls="yes" >}}
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']
      css_class: video-narrow


  - block: markdown
    content:
      title: |
        Concrete printing by RKPM meshfree method
      subtitle:
      text: |
        {{< video src="concrete.mp4" poster="multi-media-posters/concrete.png" controls="yes" >}}
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']
      css_class: video-narrow

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