---
permalink: /devlab_alumni/
title: "Alumni"
---

<style>
  /* DevLab Navigation Styles */
  .devlab-nav {
    position: relative;
    background: #f8f9fa;
    border-bottom: 1px solid #e9ecef;
  }

  .devlab-links {
    display: flex;
    flex-wrap: wrap;
    justify-content: flex-start;
    align-items: center;
    margin: 0;
    padding: 0;
    list-style: none;
    gap: 0;
  }

  .devlab-menu-item {
    margin: 0;
    padding: 0;
  }

  .devlab-menu-item a {
    display: block;
    padding: 1rem 1.5rem;
    color: #333;
    text-decoration: none;
    font-weight: 500;
    transition: all 0.2s ease;
    border-bottom: 3px solid transparent;
  }

  .devlab-menu-item a:hover {
    color: #383838;
    background-color: #e9ecef;
    border-bottom-color: #383838;
  }

  .devlab-menu-item a:active {
    background-color: #dee2e6;
  }

  /* Responsive navigation design */
  @media (max-width: 768px) {
    .devlab-links {
      flex-direction: column;
      align-items: stretch;
    }

    .devlab-menu-item {
      border-bottom: 1px solid #e9ecef;
    }

    .devlab-menu-item:last-child {
      border-bottom: none;
    }

    .devlab-menu-item a {
      padding: 0.75rem 1rem;
      text-align: left;
    }

    .devlab-menu-item a:hover {
      background-color: #f8f9fa;
      border-bottom-color: transparent;
    }
  }

  @media (max-width: 480px) {
    .devlab-menu-item a {
      padding: 0.5rem 0.75rem;
      font-size: 0.9rem;
    }
  }

  /* DevLab Grid Layout Styles */
  .devlab-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }
  
  .devlab-item {
    width: calc(33.33% - 10px);
    margin: 5px;
    padding: 5px;
    box-sizing: border-box;
  }

  .devlab-image-container {
    height: 300px;
    overflow: hidden;
  }

  .devlab-image-container img {
    height: 100%;
    width: 100%;
    object-fit: cover;
    display: block;
  }

  /* Media queries for responsive layout */
  @media (max-width: 992px) {
    .devlab-item {
      width: calc(50% - 10px);
    }
  }

  @media (max-width: 768px) {
    .devlab-item {
      width: calc(100% - 10px);
    }
  }

  /* DevLab Search Functionality Styles */
  .devlab-search-container {
    margin: 20px 0;
    text-align: left;
  }

  .devlab-search-input {
    width: 300px;
    padding: 10px;
    border: 2px solid #ddd;
    border-radius: 5px;
    font-size: 16px;
    margin-bottom: 10px;
  }

  .devlab-search-input:focus {
    outline: none;
    border-color: #007bff;
  }

  .devlab-no-results {
    text-align: center;
    padding: 20px;
    font-style: italic;
    color: #666;
    display: none;
  }

  .devlab-hidden {
    display: none !important;
  }
</style> 

<!-- =============================Dev Lab header Below========================== -->

{% include devlab-masthead.html %}

<!-- Search functionality -->
<!-- DevLab Search functionality -->
<div class="devlab-search-container">
  <input type="text" id="devlabSearchInput" class="devlab-search-input" placeholder="Search by name, institution, or role...">
  <div id="devlabNoResults" class="devlab-no-results">No results found. Try a different search term.</div>
</div>

<!-- =============================Dev Lab Content Below========================== -->
<!-- /////////////////////////container start-->
<!-- /////////////////////////container start-->
<div class="devlab-container" id="devlabPeopleContainer">
<!-- /////////////////////////container start-->
<!-- /////////////////////////container start-->

<!-- /////////////////////////Item start -->
<div class="devlab-item" data-search="james allen associate research fellow international food policy research institute ifpri phd graduation year 2023">

<a target="_blank" href="https://www.jamesalleniv.com/">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Allen-James-2-scaled-e1631034518583.jpg'></div>

<strong>James Allen</strong><br>
</a>

Associate Research Fellow<br>

International Food Policy Research Institute (IFPRI)<br>

<strong>Ph.D. Graduation Year: </strong>2023

</div>
<!-- /////////////////////////Item end -->

<!-- /////////////////////////Item start -->

<div class="devlab-item" data-search="robert beckemeyer predoctoral scholar federal reserve bank of kansas city ba graduation year 2024">

<a href="#">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/RobertBeckemeyerDevEcon-e1683910845272.jpg'></div>

<strong> Robert Beckemeyer </strong><br>
</a>
Predoctoral Scholar <br>
Federal Reserve Bank of Kansas City<br>
<strong>BA Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item -->

<div class="devlab-item" data-search="rohan bhargava predoctoral scholar federal reserve bank of new york ba graduation year 2024">

<a href="#">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2022/07/RohanDevEconPic-scaled-e1659123003737.jpg'></div>

<strong> Rohan Bhargava</strong><br>
</a>
Predoctoral Scholar<br>
Federal Reserve Bank of New York<br>
<strong>BA Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item start -->

<div class="devlab-item" data-search="moustafa el-kashlan phd student department of economics university of chicago ba graduation year 2019">

<a href="#">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/09/MoustafaPicDevEcon-2-e1696042175474.jpg'></div>

<strong>Moustafa El-Kashlan</strong><br>
</a>
Ph.D. Student<br>
Department of Economics,
<br>University of Chicago<br>
<strong>BA Graduation Year: </strong>2019

</div>

<!-- /////////////////////////Item -->

<div class="devlab-item" data-search="maximilian huppertz research economist bank of england phd graduation year 2024">

<a href="https://maxhuppertz.github.io/">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Huppertz.png'></div>

<strong> Maximilian Huppertz</strong><br>
</a>
Research Economist<br>
Bank of England<br>
<strong>Ph.D. Graduation Year: </strong>2024

</div>

<!-- /////////////////////////Item -->

<div class="devlab-item" data-search="zara jacob predoctoral scholar federal reserve bank of new york ba graduation year 2025">

<a href="#">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2024/02/ZaraDevEcon-scaled-e1708381090386.jpg'></div>

<strong> Zara Jacob</strong><br>
</a>
Predoctoral Scholar<br>
Federal Reserve Bank of New York<br>
<strong>BA Graduation Year: </strong>2025

</div>

<!-- /////////////////////////Item -->
<div class="devlab-item" data-search="raelynn ruoran li phd student department of marketing wharton school of business university of pennsylvania bs graduation year 2024">

<a href="#">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/RuroranLiDevLab-e1683172076641.jpeg'></div>

<strong>Raelynn (Ruoran) Li</strong><br>
</a>
Ph.D. Student<br>
Department of Marketing, <br>Wharton School of Business, University of Pennsylvania<br>
<strong>BS Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item end -->
<!-- /////////////////////////Item start -->
<div class="devlab-item" data-search="jinghao liu phd student department of economics yale university ba graduation year 2024">

<a href="#">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/JinghaoLiuDevEcon-e1683911309229.jpg'></div>

<strong>Jinghao Liu</strong><br>
</a>
Ph.D. Student<br>
Department of Economics, <br>Yale University<br>
<strong>BA Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item -->

<div class="devlab-item" data-search="nicholas martens predoctoral scholar booth school of business university of chicago ba graduation year 2024">

<a href="https://www.linkedin.com/in/nicholas-l-martens">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/01/NickMartensDevEcon-e1674836569380.jpg'></div>

<strong>Nicholas Martens</strong><br>
</a>
Predoctoral Scholar<br>
Booth School of Business, University of Chicago<br>
<strong>BA Graduation Year: </strong>2024

</div>

<!-- /////////////////////////Item start -->
<div class="devlab-item" data-search="ryan mcway phd student department of applied economics university of minnesota predoc years 2020-2022">

<a href="#">

<div class="devlab-image-container">
<img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Ryan-McWay-2-e1632013751645.jpg'></div>

<strong>Ryan McWay</strong><br>
</a>
Ph.D. Student<br>
Department of Applied Economics,<br>
University of Minnesota<br>
<strong>Predoc Years: </strong>2020-2022

</div>

<!-- /////////////////////////Item -->
<div class="devlab-item" data-search="russell morton assistant professor simon school of business university of rochester phd graduation year 2024">

<a href="https://sites.lsa.umich.edu/rpmorton/">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Russell-Morton-e1631037256887.jpg'></div>

<strong>Russell Morton</strong><br>
</a>
Assistant Professor<br>
Simon School of Business, University of Rochester<br>
<strong>Ph.D. Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item -->

<div class="devlab-item" data-search="emir murathanoglu assistant professor department of economics oberlin college phd graduation year 2024">

<a href="https://lsa.umich.edu/econ/people/phd-student<br>s/emir-murathanoglu.html">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2022/02/Emir-Murathanoglu-e1644421354164.jpeg'></div>

<strong>Emir Murathanoglu</strong><br>
</a>
Assistant Professor<br>
Department of Economics, Oberlin College<br>
<strong>Ph.D. Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item -->

<div class="devlab-item" data-search="rita neves phd student department of economics nova university lisbon predoc years 2022-24">

<a href="#">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2022/07/RitaNeves-e1658300099108.jpeg'></div>

<strong>Rita Neves</strong><br>
</a>
Ph.D. Student<br>
Department of Economics, <br>Nova University, Lisbon<br>
<strong>Predoc Years: </strong>2022-24

</div>

<!-- /////////////////////////Item -->

<div class="devlab-item" data-search="nyah phillips phd student department of economics university of california berkeley predoc years 2023-25">

<a href="#">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/NyahPDevEcon-e1683911613701.jpg'></div>

<strong>Nyah Phillips</strong><br>
</a>
Ph.D. Student<br>
Department of Economics, <br>University of California, Berkeley<br>
<strong>Predoc Years: </strong>2023-25

</div>

<!-- /////////////////////////Item -->

<div class="devlab-item" data-search="hadin sayed predoctoral scholar university of notre dame ba graduation year 2024">

<a href="#">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/01/HadinSayedDevEcon-e1674931048814.png'></div>

<strong>Hadin Sayed</strong><br>
</a>
Predoctoral Scholar<br>
University of Notre Dame<br>
<strong>BA Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item end -->

<div class="devlab-item" data-search="yu shi phd student department of economics yale university ba graduation year 2024">

<a href="#">

<div class="devlab-image-container">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/01/YuShiDevEcon-scaled-e1674932042501.jpg'></div>

<strong>Yu Shi</strong><br>
</a>
Ph.D. Student<br>
Department of Economics, <br>Yale University<br>
<strong>BA Graduation Year: </strong>2024

</div>
<!-- /////////////////////////Item end -->

<!-- /////////////////////////Item start -->
<div class="devlab-item" data-search="jared stolove phd student department of economics yale university ba graduation year 2020">

<a target="_blank" href="https://www.linkedin.com/in/jared-stolove-4477b427/" >

<div class="devlab-image-container">
<img src='https://devecon.umich.edu/wp-content/uploads/2023/06/JaredStoloveDevEcon-scaled-e1686080761725.jpg'></div>
<strong>Jared Stolove</strong><br>
</a>
Ph.D. Student<br>
Department of Economics, <br>Yale University<br>
<strong>BA Graduation Year: </strong>2020

</div>

<!-- /////////////////////////Item -->

<div class="devlab-item" data-search="daniel velásquez-cabrera assistant professor department of economics claremont-mckenna university phd graduation year 2025">

<a  target="_blank" href="https://dvelasquezc.github.io/">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2021/09/Daniel_Vasquez-2-e1632778136973.jpeg'></div>

<strong>Daniel Velásquez-Cabrera</strong><br>
</a>
Assistant Professor<br>
Department of Economics, <br>Claremont-McKenna University<br>
<strong>Ph.D. Graduation Year: </strong>2025

</div>
<!-- /////////////////////////Item -->

<div class="devlab-item" data-search="laura wang phd student kellogg school of business northwestern university ba graduation year 2025">

<a href="#">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/11/LauraWangDevEcon-scaled-e1700209188122.jpg'></div>

<strong>
Laura Wang</strong><br>
</a>
Ph.D. Student<br>
Kellogg School of Business, <br>Northwestern University<br>
<strong>BA Graduation Year: </strong>2025
</div>

<!-- /////////////////////////Item -->

<div class="devlab-item" data-search="ann yang predoctoral scholar federal reserve bank of chicago ba graduation year 2025">
<a href="#">
<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/11/Ann-PhotoDevEcon-e1700208769929.jpg'></div>
<strong>Ann Yang</strong><br>
</a>
Predoctoral Scholar<br>
Federal Reserve Bank of Chicago<br>
<strong>BA Graduation Year: </strong>2025

</div>

<!-- /////////////////////////Item start -->
<div class="devlab-item" data-search="yvette zhang phd student department of economics yale university ba graduation year 2024">

<a href="#">

<div class="devlab-image-container"><img src='https://devecon.umich.edu/wp-content/uploads/2023/05/YvetteZDevLab-e1683171618872.jpg'></div>
<strong>Yvette Zhang</strong><br>
</a>
Ph.D. Student<br>
Department of Economics, <br>Yale University<br>
<strong>BA Graduation Year: </strong>2024
</div>
<!-- /////////////////////////Item end -->

<!-- ///////////////////////// leave  this Item-->
<div class="devlab-item">
</div>
<!-- /////////////////////////leave  this Item- -->

<!-- /////////////////////////container End-->
<!-- /////////////////////////container End-->
<!-- /////////////////////////container End-->
<!-- /////////////////////////container End-->

<script>
document.addEventListener('DOMContentLoaded', function() {
    const searchInput = document.getElementById('devlabSearchInput');
    const peopleContainer = document.getElementById('devlabPeopleContainer');
    
    if (searchInput && peopleContainer) {
        const items = peopleContainer.querySelectorAll('.devlab-item');
        const noResults = document.getElementById('devlabNoResults');

        searchInput.addEventListener('input', function() {
            const searchTerm = this.value.toLowerCase().trim();
            let visibleCount = 0;

            items.forEach(item => {
                const searchData = (item.getAttribute('data-search') || '').toLowerCase();
                if (searchTerm === '' || searchData.includes(searchTerm)) {
                    item.style.display = 'block';
                    visibleCount++;
                } else {
                    item.style.display = 'none';
                }
            });

            noResults.style.display = (visibleCount === 0 && searchTerm !== '') ? 'block' : 'none';
        });

        searchInput.addEventListener('change', function() {
            if (this.value === '') {
                items.forEach(item => item.style.display = 'block');
                noResults.style.display = 'none';
            }
        });
    }
});
</script>
