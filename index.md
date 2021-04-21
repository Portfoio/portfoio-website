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
    rectangle: true
    headline: Generate optimized Portfolios
    content: Choose your settings for our AI, relax and let our AI do your work. Choose from a set of optimized portfolios based on your preferneces.
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


  - template: content-feature
    block: feature-1
    media_alignment: Left
    slug: recommendation
    headline: Find the perfect ETF
    content: Tell us what your preferences are and what you bought and we show you a optimal ETF that matches your portfolio.
    media:
      image: "/assets/images/mac-mock.png"
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
      content: Tell our AI what you are looking for. Select what asset types you are looking for (ETFs, Stocks, Crypotcurrencies).
    col_2:
      headline: Our AI learns constantly
      content: Our AI, based on genetic algorithms, searches thorugh hundredthousand of assets and learns to combine these into diversified portfolios.
    col_3:
      headline: Invest into your portfolios
      content: You can directly start investing into your calculated optimized portfolios. No need for switching the broker, you can invest by your current broker.

 
  - template: simple-footer
    block: footer-2
    col_1: <a href="">Impressum</a>  </br> <a href="">About us</a>
    col_2: Made with ❤︎ in Münster
    cta:
      url: http://localhost:8080/register
      button_text: Register
---
