---
layout: archive
title: "DevLab"
permalink: /devlab/

---

<!-- ////////////// -->

 
<!-- > [devlab page]( /devlab_page_2/) /   [devlab page]( /devlab_page_3/) /    [devlab page]( /devlab_page_3/) /    -->
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


<!-- ///////////// -->



<!-- =============================Dev Lab home Content Below========================== -->



DevLab is the group of Michigan Ph.D. and undergraduate students working with or under the supervision of Dean Yang. DevLab members meet regularly to share their work and give feedback to one another. Current research projects in DevLab span a range of topic areas in development economics, including religion, health, international migration, remittances, colonialism, education, and labor markets. 
<br><br><br><br>
<img src='https://devecon.umich.edu/wp-content/uploads/2023/01/DevLabPic-2-e1673278974910.jpg'>
