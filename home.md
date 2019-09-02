---
layout: index
title: # should be set by _config

lang: en
lang-ref: home.md

banner:
  title: Welcome to Fullshare
  desc:
  content: |
    Fullshare Holdings Limited (HKSE: 00607.HK) is a multinational conglomerate and investment company. Founded in 2002 and listed on Hong Kong stock exchange in December 2013, Fullshare is headquartered in Nanjing, China with offices in Hong Kong, Singapore, and Australia.
  button:
    show: true
    url: "#aboutus"
    text: Continue
  image_url: 'images/background.jpg'

spotlight-about:
  title: About Us
  content: |
    <p>Fullshare Holdings Limited (“Group”; SEHK stock code: 00607.HK) has been listed on the Hong Kong Stock Exchange since the end of 2013.</p>
    <p>[expand]</p>
    <p>Fullshare Holdings Limited is a Chinese conglomerate focused on becoming a global leader in healthy living. The Group’s business can be categorized in four segments, namely, tourism, education and healthcare, property, as well as renewable energy. The group’s business and projects have expanded to Mainland China, Hong Kong, Singapore, Australia, etc.</p>
    <ul>
    <li>a constituent stock of FTSE Global Mid Cap Index</li>
    <li>a constituent stock of Hang Seng Composite Large Cap Index and an eligible stock under Southbound Trading of Shanghai-Hong Kong Connect</li>
    <li>a constituent stock of Morgan Stanley Capital International (MSCI) China Index</li>
    </ul>
    <p>[/expand]</p>
  button:
    show: true
    url: "pages/about"
    text: Learn More
  image_url: 'images/business/property/wonder_city/1.jpg'

spotlight-business:
  title: Our Business
  content: |
    <!--
    <ul class="alt">
    <li><a href="pages/tourism" class="button">Tourism</a></li>
    <li><a href="pages/education" class="button">Education & Healthcare</a></li>
    <li><a href="pages/renewable" class="button">Renewable Energy</a></li>
    <li><a href="pages/property" class="button">Property</a></li>
    </ul>
    -->
    <p>
    <a href="pages/tourism" class="button">Tourism</a>
    <a href="pages/education" class="button">Education & Healthcare</a>
    <a href="pages/renewable" class="button">Renewable Energy</a>
    <a href="pages/property" class="button">Property</a>
    </p>
  button:
    show: false
    url: "pages/business"
    text: Learn More
  image_url: 'images/business/property/yuhua_salon/3.jpg'

spotlight-governance:
  title: Corporate Governance
  content:
  button:
    show: true
    url: "pages/governance"
    text: Learn More
  image_url: 'images/business/tourism/sheraton/4.jpg'

items-contact:
  title: Contact Us
  content: Media & Investor Enquiries
  list:
    - title: Telephone
      content: <a href="tel:+852 3618 8462">+852 3618 8462</a>
      fa_class: fas fa-phone
    - title: Fax
      content: +852 3460 4237
      fa_class: fas fa-fax
    - title: Email
      content: <a href="mailto:fullshare@intelligentjoy.com">fullshare@intelligentjoy.com</a>
      fa_class: far fa-envelope
    - title: Address
      content: <a href="https://goo.gl/maps/xvcagXJyVho311Qt8" target="_blank">Unit 10-12, Level 43, Champion Tower, 3 Garden Road, Central, Hong Kong</a>
      fa_class: fas fa-map
---
<!-- Welcome Banner -->
{% include _banner.html key='' style='style5' scheme='invert' color='' size='fullscreen' content_align='left' img_pos='left' %}

<!-- About Us -->
{% include _spotlight.html key='spotlight-about' style='style1' orient='right' scheme='invert' color='' size='' content_align='left' img_pos='left' id='aboutus' %}

<!-- Our Business -->
{% comment %}
# finding font icon and formatting the item grid a bit time consumming right now
{% include _items.html key='items-businesses' style='style2' size='small' id='businesses' %}
{% endcomment %}
{% include _spotlight.html key='spotlight-business' style='style1' orient='left' scheme='' color='' size='' content_align='right' img_pos='left' id='businesses' %}


<!-- Corporate Goverance -->
{% include _spotlight.html key='spotlight-governance' style='style1' orient='right' scheme='invert' color='' size='' content_align='Center' img_pos='center' id='governance' %}

<!-- Contact Us -->
{% include _items.html key='items-contact' style='style3' size='small' id='contact' %}
