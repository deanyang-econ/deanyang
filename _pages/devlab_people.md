---
permalink: /devlab_people/
title: "People"
---

<style>
  .container {
    display: flex; /* Use flexbox */
    flex-wrap: wrap; /* Allow items to wrap onto multiple lines */
    justify-content: space-between; /* Distribute items evenly */
  }
  
  .item {
    width: calc(33.33% - 10px); /* Calculate width for 3 items with margin */
    margin: 5px; /* Add some margin for spacing */
    padding:5px;
    box-sizing: border-box; /* Include padding and border in the width */
  }

    .image-container {
    height: 280px; /* Set the desired height */
    overflow: hidden; /* Hide any overflowing content */
  }

  .image-container img {
    height: 100%; /* Set image height to 100% of parent container's height */
    width: auto; /* Let the width adjust automatically to maintain aspect ratio */
    display: block; /* Remove any extra space below image */
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
            <li class="masthead__menu-item"><a href="{{ domain }}{{ link.url }}">{{ link.title }}</a>
            </li>
          {% endfor %}
        </ul>
        <ul class="hidden-links hidden"></ul>
      </nav>
    </div>
  </div>
</div>

<!-- =============================Dev Lab Content Below========================== -->
<!-- /////////////////////////row 1 -->
<!-- /////////////////////////Item -->

<div class="container">
<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/11/EeshaDevEcon-scaled-e1700603047263.jpg'>

<strong> Eesha Acharya</strong><br>
</a>

</div>

Undergraduate Student<br>

Department of Economics, LSA

<!-- /////////////////////////Item -->

</div>
<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/05/RobertBeckemeyerDevEcon-e1683910845272.jpg'>

<strong> Robert Beckemeyer </strong><br>
</a>

</div>

Undergraduate Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2022/07/RohanDevEconPic-scaled-e1659123003737.jpg'>

<strong> Rohan Bhargava</strong><br>
</a>

</div>

Undergraduate Student<br>

Department of Economics, LSA

</div>


<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/02/briandaza-scaled-e1677185278604.jpg'>

<strong> Brian Daza</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

</div>

<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/01/JoaquinEndara-2-scaled-e1674531855820.jpg'>

<strong> Joaquin Endara</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="https://alexanderfertig.com/">
<img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Alexander-Fertig_Headshot_old-e1631110128981.jpg'>

<strong> Alexander Fertig</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA
Ford School of Public Policy

</div>

<!-- /////////////////////////row 3 -->
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2024/03/JohnAhlinDevEcon-e1710788431686.jpg'>

<strong> John Ahlin</strong><br>
</a>

</div>

Undergraduate Student<br>

Department of Economics, LSA
Department of Mathematics, LSA

<!-- /////////////////////////Item -->

</div>
<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/11/YaraGomesDevEcon-e1700210110130.jpg'>

<strong>Yara Gomes </strong><br>
</a>

</div>

Predoctoral Scholar

Population Studies Center, Institute for Social Research

</div>
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/11/Jiaxin-GuoDevEcon-e1700208477572.jpg'>

<strong>Jiaxin Guo</strong><br>
</a>

</div>

Undergraduate Student<br>

Department of Economics, LSA

</div>

<!-- /////////////////////////row 4 -->
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="https://maxhuppertz.github.io/">
<img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Huppertz.png'>

<strong> Maximilian Huppertz</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

<!-- /////////////////////////Item -->

</div>
<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2024/02/ZaraDevEcon-scaled-e1708381090386.jpg'>

<strong> Zara Jacob</strong><br>
</a>

</div>

Undergraduate Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="https://sites.google.com/view/imryoung/home">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/02/ImryoungDevEcon-e1677183661437.jpg'>

<strong> Imryoung Jeong</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

</div>


<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2022/07/HeesungKim-e1658124620972.jpg'>

<strong>Heesung Kim</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

<!-- /////////////////////////Item -->

</div>
<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/02/SeongyoonKimDevEcon-e1677184852160.jpg'>

<strong> Seongyoon Kim</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/05/Screen-Shot-2023-05-12-at-7.03.45-PM-e1683936698830.png'>

<strong>Aladdin Ko</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

</div>

<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="https://alaskievic.github.io/">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/01/AndreiDevEcon-e1674835356911.jpg'>

<strong>Andrei Arminio Laskievic</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

<!-- /////////////////////////Item -->

</div>
<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/05/RuroranLiDevLab-e1683172076641.jpeg'>

<strong>Ruoran Li</strong><br>
</a>

</div>

Undergraduate Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/05/JinghaoLiuDevEcon-e1683911309229.jpg'>

<strong>Jinghao Liu</strong><br>
</a>

</div>
Undergraduate Student<br>

Department of Economics, LSA

</div>


<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/01/ThomasLloydDevEcon-scaled-e1674835787136.jpg'>

<strong>Thomas Lloyd</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

<!-- /////////////////////////Item -->

</div>
<div class="item">
<div class="image-container">
<a href="https://laston-manja.github.io/">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/05/LastonManjaDevEcon-scaled-e1683938798775.jpg'>

<strong>Laston Manja </strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="https://www.linkedin.com/in/nicholas-l-martens">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/01/NickMartensDevEcon-e1674836569380.jpg'>

<strong>Nicholas Martens</strong><br>
</a>

</div>

Undergraduate Student<br>

PPE and Economics Major, LSA

</div>


<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/01/MARTIN.Magdalena_2022-headshot-2-e1675062347957.jpg'>

<strong>Magdalena Martin Kommer</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

<!-- /////////////////////////Item -->

</div>
<div class="item">
<div class="image-container">
<a href="https://sites.lsa.umich.edu/rpmorton/">
<img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Russell-Morton-e1631037256887.jpg'>

<strong>Russell Morton</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="https://lsa.umich.edu/econ/people/phd-student<br>s/emir-murathanoglu.html">
<img src='https://devecon.umich.edu/wp-content/uploads/2022/02/Emir-Murathanoglu-e1644421354164.jpeg'>

<strong>Emir Murathanoglu</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

</div>

<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2022/07/RitaNeves-e1658300099108.jpeg'>

<strong>Rita Neves</strong><br>
</a>

</div>

Predoctoral Scholar

Population Studies Center, Institute for Social Research

<!-- /////////////////////////Item -->

</div>
<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/02/AneeshaDevEcon-e1677182168478.jpeg'>

<strong>
Aneesha Parvathaneni</strong><br>
</a>
</div>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/05/NyahPDevEcon-e1683911613701.jpg'>

<strong>Nyah Phillips</strong><br>
</a>

</div>

Predoctoral Scholar<br>

Department of Economics, LSA

</div>


<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/01/HadinSayedDevEcon-e1674931048814.png'>

<strong>Hadin Sayed</strong><br>
</a>

</div>

Undergraduate Student<br>

Department of Economics, LSA

<!-- /////////////////////////Item -->

</div>
<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/01/YuShiDevEcon-scaled-e1674932042501.jpg'>

<strong>Yu Shi</strong><br>
</a>

</div>

Undergraduate Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/11/Ryan-SimDevEcon-e1700209790677.png'>

<strong>Ryan Sim</strong><br>
</a>

</div>

Undergraduate Student<br>

Department of Economics, LSA

</div>


<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/05/NathanSundayDevLabPic2-scaled-e1683172498191.jpg'>

<strong>Nathan Sunday</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

<!-- /////////////////////////Item -->

</div>
<div class="item">
<div class="image-container">
<a href="https://dvelasquezc.github.io/">
<img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Daniel_Vasquez-2-e1632778136973.jpeg'>

<strong>Daniel Velásquez-Cabrera</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/11/LauraWangDevEcon-scaled-e1700209188122.jpg'>

<strong>
Laura Wang</strong><br>
</a>
</div>

Undergraduate Student<br>

Department of Economics, LSA
Department of Mathematics, LSA

</div>

<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2022/07/YuqingWang-e1658113812764.jpg'>

<strong>Yuqing Wang</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

<!-- /////////////////////////Item -->

</div>
<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/11/Ann-PhotoDevEcon-e1700208769929.jpg'>

<strong>Ann Yang</strong><br>
</a>

</div>

Undergraduate Student<br>

Department of Economics, LSA

</div>

<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="http://tyentzen.com/">
<img src='https://devecon.umich.edu/wp-content/uploads/2022/09/TrianaYentzen-scaled-e1663537416574.jpg'>

<strong>Triana Yentzen</strong><br>
</a>

</div>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/05/YvetteZDevLab-e1683171618872.jpg'>

<strong>Yvette Zhang</strong><br>
</a>
</div>

Undergraduate Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->


<div class="item">
<div class="image-container">
<a href="#">
<img  src='/deanyang/files/profiles/Edgar Zhu.JPG'>

<strong>Edgar Zhu,</strong><br>
</a>
</div>

Undergraduate Student<br>
Department of Economics, LSA

</div>
<!-- /////////container Div end///////// -->
</div>