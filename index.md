---
layout: index
title: # should be set by _config

banner:
  title: Welcome to Fullshare
  desc:
  content: |
    Fullshare Holdings Limited (HKSE: 00607.HK) is a multinational conglomerate and investment company. Founded in 2002 and listed on Hong Kong stock exchange in December 2013, Fullshare is headquartered in Nanjing, China with offices in Hong Kong, Singapore, and Australia.
  button:
    show: true
    url: "#aboutus"
    text: Get Started
  image_url: 'images/banner.jpg'

spotlight-about:
  title: About Us
  content: |
    <p>Fullshare Holdings Limited (“Group”; SEHK stock code: 00607.HK) has been listed on the Hong Kong Stock Exchange since the end of 2013.</p>
    <p>Fullshare Holdings Limited is a Chinese conglomerate focused on becoming a global leader in healthy living. The Group’s business can be categorized in four segments, namely, tourism, education and healthcare, property, as well as renewable energy. The group’s business and projects have expanded to Mainland China, Hong Kong, Singapore, Australia, etc.</p>
    <ul>
    <li>a constituent stock of FTSE Global Mid Cap Index</li>
    <li>a constituent stock of Hang Seng Composite Large Cap Index and an eligible stock under Southbound Trading of Shanghai-Hong Kong Connect</li>
    <li>a constituent stock of Morgan Stanley Capital International (MSCI) China Index</li>
    </ul>
  button:
    show: true
    url: "pages/aboutus"
    text: Learn More
  image_url: 'images/spotlight01.jpg'

---
<!-- Welcome Banner -->
{% include _banner.html key='' style='style5' scheme='' color='' size='fullscreen' content_align='left' img_pos='left' %}
<!-- About Us -->
{% include _spotlight.html key='spotlight-about' style='style1' orient='right' scheme='' color='' size='' content_align='left' img_pos='left' id='aboutus' %}

{% comment %}

<!-- Our Business -->
{% include _spotlight.html key='spotlight1' style='style1' orient='right' scheme='' color='' size='' content_align='left' img_pos='left' id='' %}
<!-- Corporate Goverance -->
{% include _spotlight.html key='spotlight1' style='style1' orient='right' scheme='' color='' size='' content_align='left' img_pos='left' id='' %}
<!-- Contact Us -->
{% include _spotlight.html key='spotlight1' style='style1' orient='right' scheme='' color='' size='' content_align='left' img_pos='left' id='' %}

{% endcomment %}
