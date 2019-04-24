---
layout: page
title: Corporate Governance | Fullshare Holding Ltd.
nav_fname: nav_governance
banner:
  title: Corporate Governance
  desc:
  content:
  button:
    show: true
    url: "#task"
    text: Continue
  image_url: '../images/business/education/sparrow_early_learning/6.jpg'

spotlight-risk_management:
  title: Risk Management
  content: |
    <p><b>Risk Management Working Group</b></p>

    <p>Composed of 5 regular members, including the Chief Operating Officer and one member from the Company’s Finance Department, Legal Department, Human Resources Department and Internal Audit Department, respectively. Chaired by the Company’s Chief Operating Officer who is in charge of risk management.</p>

    <ul>
    <li>To rationalize the Company’s risk management system, monitor and inspect daily operations</li>
    <li>To report to the risk management committee</li>
    </ul>

    <p><b>Risk management Committee</b></p>

    <p>Composed by at least three directors appointed by the Board of Directors of the Company. The committee can invite other persons (including directors, senior management and external advisors) to attend the meeting.</p>

    <ul>
    <li>To assist the Board of Directors in assessing and resolving the characteristics and level of risk they are willing to bear while achieving strategic goals</li>
    <li>To assist the Board of Directors in the supervision of risk management and the design, implementation and oversight of internal monitoring system</li>
    <li>To provide advisory services to the Board of Directors in regard to the Company’s risk-related issues</li>
    <li>To review and assess regularly the adequacy and effectiveness of the Company’s risk management framework, internal control systems and risk management policies, procedures and systems</li
    </ul>
  button:
    show: true
    url: "#"
    text: Back to Top
  image_url: '../images/business/tourism/sheraton/4.jpg'
---
<!-- Welcome Banner -->
{% include _banner.html key='' style='style5' scheme='invert' color='' size='fullscreen' content_align='left' img_pos='left' %}

<!-- Task -->
<!-- Wrapper -->
<section class="wrapper style2 align-center" id = "task">
    <div class="inner medium">
      <h2 >Management Team</h2>

      <section class="align-left" >
        <h2>Executive Directors</h2>
        {% include expandable_ppl.html fname='team_exec_dir' %}
      </section>

      <section class="align-left">
        <h2>Independent Non-executive Directors</h2>
        {% include expandable_ppl.html fname='team_indy_dir' %}
      </section>

      <section class="align-left">
        <h2>Senior Management</h2>
        {% include expandable_ppl.html fname='team_senior_mgt' %}
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

<!-- Risk Management -->
{% include _spotlight.html key='spotlight-risk_management' style='style1' orient='left' scheme='' color='' size='' content_align='left' img_pos='center' id='risk_management' %}

<!-- Organizational Chart -->
<!-- We need to make an include to generate a table here -->
