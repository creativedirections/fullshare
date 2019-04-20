---
layout: page
title: About Us
nav_fname: nav_about
banner:
  title: Company Strategy
  desc:
  content: |
    <ul>
      <li>strategically develop in healthcare and renewable energy industries</li>
      <li>build up both core operation platform and service provider brands</li>
      <li>acquire high quality brands, link China market with overseas, build up the whole industry link</li>
      <li>develop both heavy-asset projects and light-asset business</li>
    </ul>
  button:
    show: true
    url: "#team"
    text: Continue
  image_url: '../images/background.jpg'

banner-office:
  title: Global Office
  desc:
  content: this is a place holder for the global office map
  button:
    show: true
    url: "#"
    text: Back to Top
  image_url: '../images/background.jpg'
---
<!-- Welcome Banner -->
{% include _banner.html key='' style='style5' scheme='invert' color='' size='fullscreen' content_align='left' img_pos='left' %}

<!-- Management Team -->
<!-- Wrapper -->
<section class="wrapper style2 align-center" >
    <div class="inner medium">
      <h2 >Management Team</h2>

      <section class="align-left" id = "team" >
        <h2>Executive Directors</h2>
        {% include expandable_ppl.html fname='team_exec_dir' %}
      </section>

      <section class="align-left">
        <h2>Independent Non-executive Directors</h2>
        {% include expandable_ppl.html fname='team_exec_dir' %}
      </section>

      <section class="align-left">
        <h2>Senior Management</h2>
        {% include expandable_ppl.html fname='team_exec_dir' %}
      </section>

    <ul class="actions vertical">
      <li><a href="#" class="button">Back to Top</a></li>
    </ul>
    </div>
    <!--
    <div class="image">
      <img src="../images/spotlight01.jpg" alt="" />
    </div>
    -->
</section>

<!-- Global Office -->
{% include _banner.html key='banner-office' style='style5' scheme='invert' color='' size='fullscreen' content_align='left' img_pos='left' id='office' %}
