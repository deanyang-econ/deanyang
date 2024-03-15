---
permalink: /devlab_schedule/
title: "Schedule"
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

<br><br><br>
<!-- ## [DevLab Schedule](https://docs.google.com/spreadsheets/d/1HOyqC_CDeIn53g3T7QMLI-wD6xLXZI1h6tHvCIonjgM/edit?pli=1#gid=2128004824)  -->
<strong>DevLab Schedule</strong>
<a class="btn" href="https://docs.google.com/spreadsheets/d/1HOyqC_CDeIn53g3T7QMLI-wD6xLXZI1h6tHvCIonjgM/edit?pli=1#gid=2128004824" target="_blank">Open</a>