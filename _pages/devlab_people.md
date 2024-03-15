---
permalink: /devlab_people/
title: "People"
---

<style>
 .row {
     display: flex;
     flex-wrap: wrap;
 }

 .col-md-4 {
     flex: 1;
     padding: 10px;
     box-sizing: border-box;
     /* border: 1px solid #ccc; */
 }

 @media (max-width: 768px) {
     .col-md-4 {
         flex: 0 0 100%;
     }
 }
 </style>
<!-- =============================Dev Lab header Below========================== -->

<div class="masthead">
  <div class="masthead__inner-wrap">
    <div class="masthead__menu">
      <nav id="" class="greedy-nav">
        <!-- <button><div class="navicon"></div></button> -->
        <ul class="visible-links">
                
{% for link in site.data.devlab-navigation.devlab-nav %}
            {% if link.url contains 'http' %}
              {% assign domain = '' %}
              {% else %}
              {% assign domain = base_path %}
            {% endif %}
            <li class="masthead__menu-item"><a href="{{ domain }}{{ link.url }}">{{ link.title }}</a></li>
          {% endfor %}
        </ul>
        <ul class="hidden-links hidden"></ul>
      </nav>
    </div>
  </div>
</div>

<!-- =============================Dev Lab Content Below========================== -->
<!-- /////////////////////////row 1 -->
<div class="row">
<div class="col-md-4">

<img src='https://devecon.umich.edu/wp-content/uploads/2023/11/EeshaDevEcon-scaled-e1700603047263.jpg'>

<strong> Eesha Acharya</strong><br>
Undergraduate Student

Department of Economics, LSA

</div>
<div class="col-md-4">

<img src='https://devecon.umich.edu/wp-content/uploads/2023/05/RobertBeckemeyerDevEcon-e1683910845272.jpg'>

<strong> Robert Beckemeyer </strong><br>
Undergraduate Student

Department of Economics, LSA

</div>

<div class="col-md-4">

<img src='https://devecon.umich.edu/wp-content/uploads/2022/07/RohanDevEconPic-scaled-e1659123003737.jpg'>

<strong> Rohan Bhargava</strong><br>
Program Manager, Development Economics @ Michigan, Undergraduate Student

Department of Economics, LSA

</div>

</div>

<!-- /////////////////////////row 2 -->


<div class="row">
<div class="col-md-4">

<img src='https://devecon.umich.edu/wp-content/uploads/2023/02/briandaza-scaled-e1677185278604.jpg'>

<strong> Brian Daza</strong><br>
Ph.D. Student

Department of Economics, LSA

</div>
<div class="col-md-4">

<img src='https://devecon.umich.edu/wp-content/uploads/2023/01/JoaquinEndara-2-scaled-e1674531855820.jpg'>

<strong> Joaquin Endara</strong><br>
Ph.D. Student

Department of Economics, LSA

</div>

<div class="col-md-4">

<img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Alexander-Fertig_Headshot_old-e1631110128981.jpg'>

<strong> Alexander Fertig</strong><br>
Ph.D. Student

Department of Economics, LSA
Ford School of Public Policy

</div>

</div>