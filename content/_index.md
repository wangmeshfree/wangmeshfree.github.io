---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Wang's Research Group|
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        **Department of Mechanics and Aerospace Engineering, Southern University of Science and Technology, Shenzhen, CHINA.**

        **南方科技大学力学与航空航天工程系**


        **We have 1 postdoc postion available immediately, 1 PhD position for the fall 2025, and multiple master student positions for the fall 2025. Please feel free to send the CV and a brief introduction of your research and youself to: wangjr@sustech.edu.cn**

        **课题组目前有一个博士后位置空缺。此外，我们计划招收一名2025年秋季入学的博士研究生，以及多名硕士研究生。所有职位的具体待遇参照南方科技大学标准执行。请有意应聘的同学请将申请简历以及个人介绍发送至邮箱：wangjr@sustech.edu.cn**


  - block: collection
    content:
      title: Recent & Upcoming Events
      subtitle:
      text:
      count: 1
      filters:
        # author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: event
    design:
      view: card
      columns: '1'


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


  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 2
      filters:
        # author: ''
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