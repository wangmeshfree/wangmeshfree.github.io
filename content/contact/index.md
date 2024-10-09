---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-

      email: wangjr@sustech.edu.cn
      phone: +86 0755-8801-1432
      address: 
        street: 1088 Xueyuan Blvd, Nanshan
        city: Shenzhen
        region: Guangdong
        postcode: '518055'
        country: CHINA
        country_code: CHN
      coordinates:
        latitude: '22.5940'
        longitude: '113.9989'
      directions: Room 819, North Tower, College of Engineering, SUSTech
      # appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
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
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
