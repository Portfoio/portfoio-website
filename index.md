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
    slug: features
    headline: Diversify your Portfolio with <strong>AI</strong>
    content:
      Upload your portfolio and our AI shows you options to diversify your portfolio.
    cta:
      enabled: true
      url: http://localhost:8080
      button_text: "Start"
    image:
      image: "/assets/images/DashboardPortfolioDetail.png"
      alt_text: Product Shot


  - template: content-feature
    block: feature-1
    media_alignment: Left
    slug: diversify
    headline:
      Find out how well diversified your portfolio is
    content:
      Quickly get insights into your portfolio and find assets which complements your portfolio.
    media:
      image: "/assets/images/iphone-mock.png"
      alt_text: Mobile view of the Dashboard


  - template: content-feature
    block: feature-1
    media_alignment: Right
    slug: how-does-it-work
    headline:
      How does it work?
    content:
      Our AI is based on state-of-the-art algorithms that are otherwise only used by professional hedge fund managers.
      <br>
      <br>
      This algorithm compares thousands of assets to your portfolio and picks the ones that best complement and balance your portfolio.
    media:
      image: "/assets/images/iphone-mock.png"
      alt_text: Mobile view of the Dashboard


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
