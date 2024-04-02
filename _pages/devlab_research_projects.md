---
permalink: /devlab_research_projects/
title: "Research Projects"

---

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
* [Health and Development in Mozambique](https://fordschool.umich.edu/mozambique-research). What are the barriers to improving public health outcomes in the context of HIV and COVID-19? _Funders: USAID, NIH_.
 

* [War Mobilization and Economic Development](https://sites.lsa.umich.edu/deanyang/wp-content/uploads/sites/205/2024/02/parvathaneni-yang-2024-war-mobilization-india.pdf). How did British demand for war materiel during World War II affect long-run industrialization in India? _Funder: Michigan Institute for Teaching and Research in Economics (MITRE), Department of Economics_. 
 

* <ins>Religious Taboos and Obligations</ins>. What economic factors affect peoples’ decisions to join religious groups? _Funder: MITRE_.
 

* <ins>The Green Revolution and Global Population</ins>. How did the technological gains from the Green Revolution affect the size and distribution of population on our planet? _Funders: MITRE, Population Studies Center (via NIH NICHD center grant)_. 
 

* <ins>Virtual Jobs</ins>. What are the barriers facing new college graduates in Sub-Saharan Africa who seek to participate in the global remote (virtual) job market? _Funder: J-PAL Jobs and Opportunity Initiative_.