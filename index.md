---
layout: blocks
title: Portfoio
date: 2017-11-22T23:00:00.000+00:00
page_sections:


  - template: navigation-header-w-button
    block: header-2
    logo: "/assets/logos/logo.svg"
    navigation:
      - link: "#how-does-it-work"
        link_text: How does it work?
    cta:
      url: http://localhost:8080/register
      button_text: Register


  - template: hero-banner-w-image
    block: hero-2
    slug: hero
    headline: <strong>Diversify your Portfolio</strong><br> with the power of AI
    content:
    cta:
      enabled: true
      url: http://localhost:8080
      button_text: "Go to the Tool"
    image:
      image: "/assets/images/iphone-mock.png"
      alt_text: Product Shot


  - template: content-feature
    block: feature-1
    media_alignment: Left
    slug: generate
    headline: Generate optimized Portfolios
    content: Choose your settings and prefernces, relax and let our algorithm do your work. Choose from a set of optimized portfolios based on your risk return preferneces.
    media:
      image: "/assets/images/mac-mock.png"
      alt_text: Mobile view of the Dashboard
    cta:
      enabled: true
      url: http://localhost:8080
      button_text: "Try the Beta"


  - template: content-feature
    block: feature-1
    media_alignment: Right
    slug: diversify
    headline: Diversify your Portfolio
    content: Tell us what assets your already bought and recieve possibilities to diversity your portfolio and lower the risk of fluctuations.
    media:
      image: "/assets/images/iphone-mock.png"
      alt_text: Mobile view of the Dashboard
    cta:
      enabled: true
      url: http://localhost:8080/register
      button_text: "Register"


  - template: 3-column-text
    block: three-column-1
    slug: how-does-it-work
    headline: How does it work?
    col_1:
      headline: Choose your specification
      content: Select your country, the asset type you are interested in and the timerage of which the AI learns.
    col_2:
      headline: Our AI learns from the past
      content: Our AI, based on genetic algorithms, searches thorugh hundredthousand of assets and learns to combine these into diversified portfolios.
    col_3:
      headline: Invest into your portfolios
      content: You can directly start investing into your calculated optimized portfolios, through our service. 


  - template: 2-column-text
    block: testimonial
    slug: testimonial
    author: John Doe
    quote: With the help of Porftoio, I was able to diversify my portfolio very quickly and easily without having to shift everything around.
    media:
      image: https://images.pexels.com/photos/3785079/pexels-photo-3785079.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260
      alt_text: Profile photo
 
  - template: simple-footer
    block: footer-1
    content: Made with ❤︎ in Münster
---
