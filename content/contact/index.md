---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        周颖教授研究室位于东南大学四牌楼校区建筑学院。
        Prof. Ying Zhou's research lab is located in the School of Architecture, Sipailou Campus, Southeast University.
      email: zhouying@seu.edu.cn
      phone: 025-83792223
      address:
        street: NO.2 Sipailou
        city: Nanjing
        region: Jiangsu
        postcode: '210096'
        country: China
        country_code: CN
      coordinates:
        latitude: '32.05484751'
        longitude: '118.79478872'
      directions: 中大院3楼315 Enter Zhongda Building and take the stairs to Office 315 on Floor 3
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      appointment_url: 'https://calendly.com'
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
