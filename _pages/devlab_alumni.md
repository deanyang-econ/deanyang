---
permalink: /devlab_alumni/
title: "Alumni"
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

<!-- ///////////profile/////// -->
<div class="col-md-4">

<img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Allen-James-2-scaled-e1631034518583.jpg'>

<a href="https://www.jamesalleniv.com/" target="_blank"><strong>James Allen</strong></a><br>
Associate Research Fellow<br>

International Food Policy Research Institute (IFPRI)<br>

<strong>Ph.D. Graduation Year: </strong>2023

</div>

<!-- /////////profile///////// -->
<div class="col-md-4">

<img src='https://devecon.umich.edu/wp-content/uploads/2023/09/MoustafaPicDevEcon-2-e1696042175474.jpg'>

<strong>Moustafa El-Kashlan</strong><br>
Ph.D. Student<br>

Department of Economics,
<br>University of Chicago<br>
<strong>BA Graduation Year: </strong>2019

</div>

<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/RuroranLiDevLab-e1683172076641.jpeg'></div>

<strong>Ruoran Li</strong><br>
</a>

Ph.D. Student<br>

Department of Marketing, <br>Wharton School of Business, University of Pennsylvania<br>

<strong>BA Graduation Year: </strong>2024

</div>

<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/JinghaoLiuDevEcon-e1683911309229.jpg'></div>

<strong>Jinghao Liu</strong><br>
</a>

Masters Student<br>

Department of Economics, <br>University of Toronto<br>

<strong>BA Graduation Year: </strong>2024

</div>

<!-- //////////profile//////// -->

<div class="col-md-4">

<img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Ryan-McWay-2-e1632013751645.jpg'>

<a href="https://mcwayrm.github.io/" target="_blank"><strong>Ryan McWay</strong></a><br>
Ph.D. Student<br>

Department of Applied Economics,<br>
University of Minnesota<br>
<strong>Predoc Years: </strong>2020-2022

</div>

<!-- ////////////////// -->
</div>

<!-- /////////////////////////row 2 -->

<div class="row">

<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/01/YuShiDevEcon-scaled-e1674932042501.jpg'></div>

<strong>Yu Shi</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, <br>Yale University<br>

<strong>BA Graduation Year: </strong>2024

</div>


<!-- ///////////profile/////// -->
<div class="col-md-4">

<img src='https://devecon.umich.edu/wp-content/uploads/2023/06/JaredStoloveDevEcon-scaled-e1686080761725.jpg'><br>
<a href="https://www.linkedin.com/in/jared-stolove-4477b427/" target="_blank"><strong>Jared Stolove</strong></a><br>
Ph.D. Student<br>

Department of Economics, <br>Yale University<br>

<strong>BA Graduation Year: </strong>2020

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/YvetteZDevLab-e1683171618872.jpg'></div>

<strong>Yvette Zhang</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, <br>Yale University<br>

<strong>BA Graduation Year: </strong>2024

</div>

<!-- /////////profile///////// -->
<div class="col-md-4">


</div>

<!-- //////////profile//////// -->

<div class="col-md-4">


</div>

<!-- /////////profile end///////// -->
</div>

<!-- /////////////////////////row 2 -->
