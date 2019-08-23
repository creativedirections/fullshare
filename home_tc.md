---
layout: index
title: # should be set by _config

lang: tc
lang-ref: home.md

banner:
  title: 豐盛 Fullshare
  desc:
  content: |
    豐盛控股有限公司（豐盛）（股份代號：607.HK）為一家跨國性綜合型企業和投資公司。集團創立於2002年，在中國南京設立總部，更先後在香港、新加坡及澳洲設立辦公室。 2013年12月，成功於香港聯合交易所上市。
  button:
    show: true
    url: "#aboutus"
    text: 了解更多
  image_url: 'images/background.jpg'

spotlight-about:
  title: 關於我們
  content: |
    <p>豐盛控股有限公司（股份代號：607.HK）于2013年底於香港交易所上市。</p>
    <p>[expand]</p>
    <p>作為一家中國的綜合性企業，豐盛控股有限公司致力成為全球領先的大健康生活服務商。本集團業務聚焦於旅遊度假、教育醫療、健康地產、再生能源四大產業板塊，業務及項目遍及中國大陸、香港、新加坡、澳洲等國家和地區。</p>
    <ul>
    <li>富時全球股票中型股股份指數</li>
    <li>恒生綜合大中型股指數成份股，滬港通及深港通合資格股份</li>
    <li>摩根士丹利資本國際MSCI中國指數成份股</li>
    </ul>
    <p>[/expand]</p>
  button:
    show: true
    url: "pages_zh-hk/about_tc"
    text: 了解更多
  image_url: 'images/business/property/wonder_city/1.jpg'

spotlight-business:
  title: 我們的業務
  content: |
    <!--
    <ul class="alt">
    <li><a href="pages_zh-hk/tourism_tc" class="button">旅遊度假</a></li>
    <li><a href="pages_zh-hk/education_tc" class="button">教育醫療</a></li>
    <li><a href="pages_zh-hk/renewable_tc" class="button">再生能源</a></li>
    <li><a href="pages_zh-hk/property_tc" class="button">健康地產</a></li>
    </ul>
    -->
    <p>
    <a href="pages_zh-hk/tourism_tc" class="button">旅遊度假</a>
    <a href="pages_zh-hk/education_tc" class="button">教育醫療</a>
    <a href="pages_zh-hk/renewable_tc" class="button">再生能源</a>
    <a href="pages_zh-hk/property_tc" class="button">健康地產</a>
    </p>
  button:
    show: false
    url: "pages_zh-hk/business_tc"
    text: 了解更多
  image_url: 'images/business/property/yuhua_salon/3.jpg'

spotlight-governance:
  title: 企業管治
  content:
  button:
    show: true
    url: "pages_zh-hk/governance_tc"
    text: 了解更多
  image_url: 'images/business/tourism/sheraton/4.jpg'

items-contact:
  title: 聯繫我們
  content: 媒體及投資者查詢
  list:
    - title: 電話
      content: <a href="tel:+852 3618 8462">+852 3618 8462</a>
      fa_class: fas fa-phone
    - title: 傳真
      content: +852 3460 4237
      fa_class: fas fa-fax
    - title: 電郵
      content: <a href="mailto:fullshare@intelligentjoy.com">fullshare@intelligentjoy.com</a>
      fa_class: far fa-envelope
    - title: 公司地址
      content: <a href="https://goo.gl/maps/xvcagXJyVho311Qt8" target="_blank">香港中環花園道3號冠君大廈43樓10-12室</a>
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
