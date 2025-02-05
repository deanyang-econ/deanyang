---
permalink: /devlab_alumni/
title: "Alumni"
---

<style>
  .container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }
  
  .item {
    width: calc(33.33% - 10px); /* Adjust width for 3 items per row with margin */
    margin: 5px;
    padding: 5px;
    box-sizing: border-box;
  }

  .image-container {
    height: 300px; /* Maintain the same height for all screen sizes */
    overflow: hidden;
  }

  .image-container img {
    height: 100%;
    width: 100%; /* Ensure image fills its container */
    object-fit: cover; /* Maintain aspect ratio and fill container */
    display: block;
  }

  /* Media queries for responsive layout */
  @media (max-width: 992px) {
    .item {
      width: calc(50% - 10px); /* Adjust width for 2 items per row with margin */
    }
  }

  @media (max-width: 768px) {
    .item {
      width: calc(100% - 10px); /* Full width for single item per row */
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
<!-- /////////////////////////container start-->
<!-- /////////////////////////container start-->
<div class="container">
<!-- /////////////////////////container start-->
<!-- /////////////////////////container start-->


<!-- /////////////////////////Item start -->
<div class="item">

<a target="_blank" href="https://www.jamesalleniv.com/">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Allen-James-2-scaled-e1631034518583.jpg'></div>

<strong>James Allen</strong><br>
</a>

Associate Research Fellow<br>


International Food Policy Research Institute (IFPRI)<br>

<strong>Ph.D. Graduation Year: </strong>2023
</div>
<!-- /////////////////////////Item end -->

<!-- /////////////////////////Item start -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/RobertBeckemeyerDevEcon-e1683910845272.jpg'></div>

<strong> Robert Beckemeyer </strong><br>
</a>

Predoctoral Scholar <br>

Federal Reserve Bank of Kansas City<br>
<strong>BA Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2022/07/RohanDevEconPic-scaled-e1659123003737.jpg'></div>

<strong> Rohan Bhargava</strong><br>
</a>

Predoctoral Scholar<br>

Federal Reserve Bank of New York<br>
<strong>BA Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item start -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/09/MoustafaPicDevEcon-2-e1696042175474.jpg'></div>

<strong>Moustafa El-Kashlan</strong><br>
</a>

Ph.D. Student<br>


Department of Economics,
<br>University of Chicago<br>
<strong>BA Graduation Year: </strong>2019

</div>

<!-- /////////////////////////Item -->

<div class="item">

<a href="https://maxhuppertz.github.io/">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Huppertz.png'></div>

<strong> Maximilian Huppertz</strong><br>
</a>

Research Economist<br>

Bank of England<br>

<strong>Ph.D. Graduation Year: </strong>2024

</div>

<!-- /////////////////////////Item -->
<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/RuroranLiDevLab-e1683172076641.jpeg'></div>

<strong>Raelynn (Ruoran) Li</strong><br>
</a>

Ph.D. Student<br>

Department of Marketing, <br>Wharton School of Business, University of Pennsylvania<br>

<strong>BS Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item end -->
<!-- /////////////////////////Item start -->
<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/JinghaoLiuDevEcon-e1683911309229.jpg'></div>

<strong>Jinghao Liu</strong><br>
</a>

Masters Student<br>

Department of Economics, <br>University of Toronto<br>

<strong>BA Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="https://www.linkedin.com/in/nicholas-l-martens">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/01/NickMartensDevEcon-e1674836569380.jpg'></div>

<strong>Nicholas Martens</strong><br>
</a>

Predoctoral Scholar<br>

Booth School of Business, University of Chicago<br>

<strong>BA Graduation Year: </strong>2024

</div>


<!-- /////////////////////////Item start -->
<div class="item">

<a href="#">

<div class="image-container">
<img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Ryan-McWay-2-e1632013751645.jpg'></div>

<strong>Ryan McWay</strong><br>
</a>


Ph.D. Student<br>

Department of Applied Economics,<br>
University of Minnesota<br>
<strong>Predoc Years: </strong>2020-2022

</div>

<!-- /////////////////////////Item -->
<div class="item">

<a href="https://sites.lsa.umich.edu/rpmorton/">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Russell-Morton-e1631037256887.jpg'></div>

<strong>Russell Morton</strong><br>
</a>

Assistant Professor<br>

Simon School of Business, University of Rochester<br>

<strong>Ph.D. Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="https://lsa.umich.edu/econ/people/phd-student<br>s/emir-murathanoglu.html">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2022/02/Emir-Murathanoglu-e1644421354164.jpeg'></div>

<strong>Emir Murathanoglu</strong><br>
</a>

Assistant Professor<br>

Department of Economics, Oberlin College<br>

<strong>Ph.D. Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2022/07/RitaNeves-e1658300099108.jpeg'></div>

<strong>Rita Neves</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, <br>Nova University, Lisbon<br>

<strong>Predoc Years: </strong>2022-24


</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/01/HadinSayedDevEcon-e1674931048814.png'></div>

<strong>Hadin Sayed</strong><br>
</a>

Predoctoral Scholar<br>

University of Notre Dame<br>

<strong>BA Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item end -->

<div class="item">

<a href="#">

<div class="image-container">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/01/YuShiDevEcon-scaled-e1674932042501.jpg'></div>

<strong>Yu Shi</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, <br>Yale University<br>

<strong>BA Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item end -->

<!-- /////////////////////////Item start -->
<div class="item">

<a target="_blank" href="https://www.linkedin.com/in/jared-stolove-4477b427/" >

<div class="image-container">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/06/JaredStoloveDevEcon-scaled-e1686080761725.jpg'></div>

<strong>Jared Stolove</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, <br>Yale University<br>

<strong>BA Graduation Year: </strong>2020

</div>
<!-- /////////////////////////Item start -->
<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/YvetteZDevLab-e1683171618872.jpg'></div>

<strong>Yvette Zhang</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, <br>Yale University<br>

<strong>BA Graduation Year: </strong>2024
</div>
<!-- /////////////////////////Item end -->




<!-- ///////////////////////// leave  this Item-->
<div class="item">
</div>
<!-- /////////////////////////leave  this Item- -->

<!-- /////////////////////////container End-->
<!-- /////////////////////////container End-->
</div>
<!-- /////////////////////////container End-->
<!-- /////////////////////////container End-->


