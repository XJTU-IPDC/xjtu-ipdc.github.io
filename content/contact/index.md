---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        这里可以写一些东西
      email: keljxjtu@xjtu.edu.cn
      phone: +86 18706796441
      address:
        street: 长安区高桥街道中国西部科技创新港
        city: 西安市
        region: 陕西省
        postcode: '710000'
        country: China
        country_code: CN
      coordinates:
        latitude: '34.258621'
        longitude: '108.653935'
      directions: 泓理楼4楼5180室，5167室
      office_hours:
        - 'Weekday 09:00 to 17:00'
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
