---
layout: page
title: Investor Relation | Fullshare Holding Ltd.
nav_fname: nav_governance
banner:
  title: Investor Relation
  desc:
  content:
  button:
    show: true
    url: "#announcements"
    text: Continue
  image_url: '../images/business/education/sparrow_early_learning/6.jpg'

spotlight-risk_management:
  title: Risk Management
  content: |
    <p><b>Risk Management Working Group</b></p>

    <p>Composed of 5 regular members, including the Chief Operating Officer and one member from the Company’s Finance Department, Legal Department, Human Resources Department and Internal Audit Department, respectively. Chaired by the Company’s Chief Operating Officer who is in charge of risk management.</p>

    <p>[expand]</p>
    <ul>
    <li>To rationalize the Company’s risk management system, monitor and inspect daily operations</li>
    <li>To report to the risk management committee</li>
    </ul>
    <p>[/expand]</p>

    <p><b>Risk Management Committee</b></p>

    <p>Composed by at least three directors appointed by the Board of Directors of the Company. The committee can invite other persons (including directors, senior management and external advisors) to attend the meeting.</p>

    <p>[expand]</p>
    <ul>
    <li>To assist the Board of Directors in assessing and resolving the characteristics and level of risk they are willing to bear while achieving strategic goals</li>
    <li>To assist the Board of Directors in the supervision of risk management and the design, implementation and oversight of internal monitoring system</li>
    <li>To provide advisory services to the Board of Directors in regard to the Company’s risk-related issues</li>
    <li>To review and assess regularly the adequacy and effectiveness of the Company’s risk management framework, internal control systems and risk management policies, procedures and systems</li>
    </ul>
    <p>[/expand]</p>
  button:
    show: true
    url: "#"
    text: #Back to Top
    custom_class: icon style2 fas fa-chevron-up
  image_url: '../images/business/tourism/sheraton/4.jpg'

table_color:
  bg_row_header: "#428bca"
  bg_col_header_1: "#003366"
  bg_col_header_2: "#f5b201"

link_color: "#0a2232"

lang: en
lang-ref: governance.md
---
<!-- Welcome Banner -->
{% include _banner.html key='' style='style5' scheme='invert' color='' size='fullscreen' content_align='left' img_pos='left' %}

<!-- Announcements -->
<section class="wrapper style2 align-center" id = "announcements">
    <div class="inner medium">
      <h2>Announcements and Circulars</h2>
      <iframe style="" src="https://asia.tools.euroland.com/tools/pressreleases/?companycode=hk-607&v=ticker&lang=en-gb" width = "100%" height ="250"></iframe>

      <ul class="actions vertical">
        <li><a href="#" class="icon style2 fas fa-chevron-up"></a></li>
      </ul>
    </div>
</section>

<!-- Fact Sheet -->
<section class="wrapper style2 align-center" id = "factsheet">
    <!--<div class="inner medium">-->
      <h2>Fact Sheet</h2>
      <iframe style="" src="https://tools.euroland.com/factsheet/hk-607/factsheethtml.asp?lang=english" width = "100%" height ="750"></iframe>

      <ul class="actions vertical">
        <li><a href="#" class="icon style2 fas fa-chevron-up"></a></li>
      </ul>
    <!--</div>-->
</section>

{% comment %}
<!-- ticker_chart-->
<section class="wrapper style2 align-center" id = "ticker_chart">
    <div class="inner medium">
      <h2>Ticker Chart</h2>
      <iframe style="" src="https://asia.tools.euroland.com/tools/ticker/?companycode=hk-607&lang=en-gb" width = "100%" height ="500"></iframe>

      <ul class="actions vertical">
        <li><a href="#" class="icon style2 fas fa-chevron-up"></a></li>
      </ul>
    </div>
</section>
{% endcomment %}

<!-- Interactive Analysis -->
<section class="wrapper style2 align-center" id = "interactive_analysis">

      <h2>Interactive Analysis</h2>
      <iframe style="" src="https://asia.tools.euroland.com/tools/ia/?companycode=hk-607&v=ad&lang=en-gb" width = "100%" height ="700"></iframe>

      <ul class="actions vertical">
        <li><a href="#" class="icon style2 fas fa-chevron-up"></a></li>
      </ul>
</section>

<!-- Share Graph -->
<section class="wrapper style2 align-center" id = "share_graph">
    <div class="inner medium">
      <h2>Share Graph</h2>
      <iframe style="" src="http://asia.tools.euroland.com/tools/sharegraph/?s=1362&companycode=hk-607&lang=en-gb" width = "100%" height ="750"></iframe>

      <ul class="actions vertical">
        <li><a href="#" class="icon style2 fas fa-chevron-up"></a></li>
      </ul>
    </div>
</section>

<!-- Subscription Centre -->
<section class="wrapper style2 align-center" id = "Subscription">
  <div class="inner medium">
      <h2>Subscription Centre</h2>
      <iframe style="" src="http://asia.tools.euroland.com/tools/SubscriptionCentre2/?companycode=hk-607&lang=en-gb" width = "100%" height ="400"></iframe>

      <ul class="actions vertical">
        <li><a href="#" class="icon style2 fas fa-chevron-up"></a></li>
      </ul>
  </div>
</section>

<!-- Risk Management -->
{% include _spotlight.html key='spotlight-risk_management' style='style1' orient='left' scheme='' color='' size='' content_align='left' img_pos='center' id='risk_management' %}

<!-- Organizational Chart -->
<!-- We need to make an include to generate a table here -->
<section class="wrapper style2 align-left" id = "org_chart">
    <div class="inner medium">
      <h2>Organizational Chart</h2>

      <ul>
          <li>Most of the members of committees under the board are independent non-executive directors</li>
          <li>All committees under the board has written terms</li>
          <li>The committees under the board could seek for independent professional advice in appropriate circumstances</li>
      </ul>

      <div class="table-wrapper align-center">
        <table>
          <thead>
            <tr >
              <td></td>
              <th colspan = '3' bgcolor = "{{ page.table_color.bg_col_header_1 }}" style = "vertical-align : bottom;" class="align-center"><h3><b><font color="white">Fullshare Board of Directors</font></b></h3></th>

              <th scope="col" bgcolor = "{{ page.table_color.bg_col_header_2 }}"><font color="white">Terms of Reference</font></th>
            </tr>
          </thead>
          <tr>
            <th scope="row" bgcolor = "{{ page.table_color.bg_row_header }}">Audit Committee</th>
            <td>Mr. Chow Siu Lui (Chairman)</td>
            <td>Mr. Lau Chi Keung</td>
            <td>Mr. Tsang Sai Chung</td>
            <td><a href="../files/2_Terms-of-Reference-of-the-Audit-Committee-1.pdf" class="button fit small icon fas fa-download">PDF</a></td>
          </tr>
          <tr>
            <th scope="row" bgcolor = "{{ page.table_color.bg_row_header }}">Remuneration Committee</th>
            <td>Mr. Lau Chi Keung (Chairman)</td>
            <td>Mr. Ji Changqun</td>
            <td>Mr. Tsang Sai Chung</td>
            <td><a href="../files/3_Term-of-Reference-of-the-Remuneration-Committee-1.pdf" class="button fit small icon fas fa-download">PDF</a></td>
          </tr>
          <tr>
            <th scope="row" bgcolor = "{{ page.table_color.bg_row_header }}">Nomination Committee</th>
            <td>Mr. Ji Changqun (Chairman)</td>
            <td>Mr. Lau Chi Keung</td>
            <td>Mr. Tsang Sai Chung</td>
            <td><a href="../files/NC-Terms-of-Reference-E.pdf" class="button fit small icon fas fa-download">PDF</a></td>
          </tr>
          <tr>
            <th scope="row" bgcolor = "{{ page.table_color.bg_row_header }}">Risk Management Committee</th>
            <td>Ms. Du Wei (Chairwoman)</td>
            <td>Mr. Wang Bo</td>
            <td>Mr. Tsang Sai Chung</td>
            <td><a href="../files/5_Terms-of-Reference-of-the-Risk-Management-Committee-1.pdf" class="button fit small icon fas fa-download">PDF</a></td>
          </tr>
          <tr>
            <th scope="row" bgcolor = "{{ page.table_color.bg_row_header }}">Environmental, Social, and Governance Committee</th>
            <td>Mr. Wang Bo (Chairman)</td>
            <td>Ms. Du Wei</td>
            <td>Mr. Tsang Sai Chung</td>
            <td><a href="../files/Attachment-1_EN.pdf" class="button fit small icon fas fa-download">PDF</a></td>
          </tr>
        </table>
      </div>

      <ul class = "alt">
        <li>List of directors and their roles and functions <br><a href="../files/Attachment-2_EN.pdf" class="icon style1 fas fa-download" style="color:{{ page.link_color }};"> PDF</a></li>
        <li>Memorandum of association & Articles of association <br><a href="../files/6_Memorandum-of-Association-Articles-of-Association.pdf" class="icon style1 fas fa-download" style="color:{{ page.link_color }};"> PDF</a></li>
        <li>Procedures for Proposing a Person for Election as a Director <br><a href="../files/7_Procedures-for-Proposing-a-Person-for-Election-as-a-Director.pdf" class="icon style1 fas fa-download" style="color:{{ page.link_color }};"> PDF</a></li>
        <li>Board Diversity Policy <br><a href="../files/Board-Diversity-Policy-E.pdf" class="icon style1 fas fa-download" style="color:{{ page.link_color }};"> PDF</a></li>
        <li>Dividend Policy <br><a href="../files/Dividend-Policy-E.pdf" class="icon style1 fas fa-download"> PDF</a></li>
      </ul>

      <ul class="actions vertical">
        <li><a href="#" class="icon style2 fas fa-chevron-up"></a></li>
      </ul>
    </div>
</section>
