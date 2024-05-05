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

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/11/EeshaDevEcon-scaled-e1700603047263.jpg'></div>

<strong> Eesha Acharya</strong><br>
</a>

Undergraduate Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2024/03/JohnAhlinDevEcon-e1710788431686.jpg'></div>

<strong> John Ahlin</strong><br>
</a>

Undergraduate Student<br>

Department of Economics, LSA
Department of Mathematics, LSA

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/02/briandaza-scaled-e1677185278604.jpg'></div>

<strong> Brian Daza</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, LSA

</div>

<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/01/JoaquinEndara-2-scaled-e1674531855820.jpg'></div>

<strong> Joaquin Endara</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="https://alexanderfertig.com/">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Alexander-Fertig_Headshot_old-e1631110128981.jpg'></div>

<strong> Alexander Fertig</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, LSA
Ford School of Public Policy

</div>
<!-- /////////////////////////Item -->
<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/11/YaraGomesDevEcon-e1700210110130.jpg'></div>

<strong>Yara Gomes </strong><br>
</a>

Predoctoral Scholar

Population Studies Center, Institute for Social Research

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/11/Jiaxin-GuoDevEcon-e1700208477572.jpg'></div>

<strong>Jiaxin Guo</strong><br>
</a>

Undergraduate Student<br>

Department of Economics, LSA

</div>
<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2024/02/ZaraDevEcon-scaled-e1708381090386.jpg'></div>

<strong> Zara Jacob</strong><br>
</a>

Undergraduate Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2022/07/HeesungKim-e1658124620972.jpg'></div>

<strong>Heesung Kim</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, LSA

<!-- /////////////////////////Item -->

</div>
<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/02/SeongyoonKimDevEcon-e1677184852160.jpg'></div>

<strong> Seongyoon Kim</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/Screen-Shot-2023-05-12-at-7.03.45-PM-e1683936698830.png'></div>

<strong>Aladdin Ko</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/01/ThomasLloydDevEcon-scaled-e1674835787136.jpg'></div>

<strong>Thomas Lloyd</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, LSA

<!-- /////////////////////////Item -->

</div>
<div class="item">

<a href="https://laston-manja.github.io/">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/LastonManjaDevEcon-scaled-e1683938798775.jpg'></div>

<strong>Laston Manja </strong><br>
</a>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/01/MARTIN.Magdalena_2022-headshot-2-e1675062347957.jpg'></div>

<strong>Magdalena Martin Kommer</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2022/07/RitaNeves-e1658300099108.jpeg'></div>

<strong>Rita Neves</strong><br>
</a>

Predoctoral Scholar

Population Studies Center, Institute for Social Research

<!-- /////////////////////////Item -->

</div>
<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/02/AneeshaDevEcon-e1677182168478.jpeg'></div>

<strong>
Aneesha Parvathaneni</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/NyahPDevEcon-e1683911613701.jpg'></div>

<strong>Nyah Phillips</strong><br>
</a>

Predoctoral Scholar<br>

Department of Economics, LSA

</div>

<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/01/HadinSayedDevEcon-e1674931048814.png'></div>

<strong>Hadin Sayed</strong><br>
</a>

Undergraduate Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img  src='/deanyang/files/profiles/Arushi Sharma_photo.JPG'></div>

<strong>Arushi Sharma,</strong><br>
</a>

MAE Student,<br>
Department of Economics, LSA

</div>

<!-- /////////////////////////Item -->
<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/NathanSundayDevLabPic2-scaled-e1683172498191.jpg'></div>

<strong>Nathan Sunday</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, LSA

<!-- /////////////////////////Item -->

</div>
<div class="item">

<a href="https://dvelasquezc.github.io/">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Daniel_Vasquez-2-e1632778136973.jpeg'></div>

<strong>Daniel Velásquez-Cabrera</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/11/LauraWangDevEcon-scaled-e1700209188122.jpg'></div>

<strong>
Laura Wang</strong><br>
</a>

Undergraduate Student<br>

Department of Economics, LSA
Department of Mathematics, LSA

</div>

<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2022/07/YuqingWang-e1658113812764.jpg'></div>

<strong>Yuqing Wang</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, LSA

<!-- /////////////////////////Item -->

</div>
<div class="item">

<a href="#">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/11/Ann-PhotoDevEcon-e1700208769929.jpg'></div>

<strong>Ann Yang</strong><br>
</a>

Undergraduate Student<br>

Department of Economics, LSA

</div>

<!-- /////////////////////////Item -->

<div class="item">

<a href="http://tyentzen.com/">

<div class="image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2022/09/TrianaYentzen-scaled-e1663537416574.jpg'></div>

<strong>Triana Yentzen</strong><br>
</a>

Ph.D. Student<br>

Department of Economics, LSA

</div>
<!-- /////////////////////////Item -->

<div class="item">

<a href="#">

<div class="image-container"><img  src='/deanyang/files/profiles/Edgar Zhu.JPG'></div>

<strong>Edgar Zhu,</strong><br>
</a>

Undergraduate Student<br>
Department of Economics, LSA

</div>



<!-- /////////container Div end///////// -->
<div class="item">
<div>
</div>
