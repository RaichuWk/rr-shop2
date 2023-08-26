<script></script>



  
  <!-- 
    - #HEADER
  -->

  <header class="header">

    <!-- 
      - overlay
    -->
    <div class="overlay" data-overlay></div>

    <div class="container">

      <a href="a" class="logo">
        <img src=" ../assets/images/logo.png" alt="Supreme Homies">
      </a>

      <button class="nav-open-btn" data-nav-open-btn>
        <ion-icon name="menu-outline"></ion-icon>
      </button>

      <nav class="navbar" data-nav>

        <div class="navbar-top">
           <button class="btn-sign_in">


         <!--    <% if(is_logged) {%>-->
                 
              <a href="/profile" style="color: #FFFFFF;"><!--<%= user.username %>#<%= user.discriminator %>--></a>
              <!--   <%} else {%>-->
    <img src="../assets/images/logo.svg">
              <!--   <%}%> -->
        </button>
          <button class="nav-close-btn" data-nav-close-btn>
            <ion-icon name="close-outline"></ion-icon>
          </button>

        </div>

        <ul class="navbar-list">

          <li>
            <a href="/" class="navbar-link">Home</a>
          </li>

          <li>
            <a href="#about" class="navbar-link">About</a>
          </li>

          <li>
            <a href="#giveaway" class="navbar-link">Giveaway</a>
          </li>

          <li>
            <a href="#gears" class="navbar-link">Shop</a>
          </li>

          <li>
            <a href="#contact" class="navbar-link">Contact</a>
          </li>

        

        </ul>

        <ul class="nav-social-list">

          <li>
            <a href="/twitter" class="social-link">
              <ion-icon name="logo-twitter"></ion-icon>
            </a>
          </li>

          <li>
            <a href="/instagram" class="social-link">
              <ion-icon name="logo-instagram"></ion-icon>
            </a>
          </li>

          <li>
            <a href="/github" class="social-link">
              <ion-icon name="logo-github"></ion-icon>
            </a>
          </li>

          <li>
            <a href="/youtube" class="social-link">
              <ion-icon name="logo-youtube"></ion-icon>
            </a>
          </li>

        </ul>

      </nav>

      <div class="header-actions">

        <button class="btn-sign_in">

          <div class="icon-box">
            <!--  <% if(is_logged) {%>-->
              <img src="https://cdn.discordapp.com/avatars/<%= user.id %>/<%= user.avatar %>.png?size=512%>" >
              <!--  <%} else {%>-->
  <ion-icon name="log-in-outline"></ion-icon>
             <!--   <%}%>-->
            
          </div>

          <!--   <% if(is_logged) {%>-->
              <span><!--<%= user.username %>#<%= user.discriminator %>--></span>
          <!--  <%} else {%>-->
  <span><a href="/auth/login" style="color: #FFFFFF;">Log-in</a></span>
            <!--    <%}%> -->
        </button>

      </div>

    </div>

  </header>





  <main>
    <article>

      <!-- 
        - #HERO
      -->

      <section class="hero" id="RR SHOP">
        <div class="container">

          <p class="hero-subtitle">It's &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</p>

          <h1 class="h1 hero-title">RR SHOP</h1>

          <div class="btn-group">

<!-- <% if(is_logged) {%>-->
     <button class="btn btn-link">Dashboard</button>
  <!--          <%} else {%>-->
                <a href="/auth/login" class="btn btn-primary"><span>Login</span>

              <ion-icon name="enter-outline"></ion-icon>
            </a>
     <!--           <%}%> -->
            

          </div>

        </div>
      </section>





      <div class="section-wrapper">

        <!-- 
          - #ABOUT
        -->

        <section class="about" id="about">
          <div class="container">

            <figure class="about-banner">

              <img src=" ../assets/images/about-img.png" alt="M shape" class="about-img">

<!--               <img src=" /images/character-1.png" alt="Game character" class="character character-1">

              <img src=" /images/character-2.png" alt="Game character" class="character character-2">

              <img src=" /images/character-3.png" alt="Game character" class="character character-3"> -->

            </figure>

            <div class="about-content">

              <p class="about-subtitle">Find Developer team</p>

              <h2 class="about-title">Experience just for Discord Developers <strong>offer</strong> </h2>

              <p class="about-text">
                We are here to provide you different API's to make discord application. We will show you how you can make your discord application more powerfull and advance.
              </p>

              <p class="about-bottom-text">
                <ion-icon name="arrow-forward-circle-outline"></ion-icon>

                <span>Thanks for visiting our site</span>
              </p>

            </div>

          </div>
        </section>





        <!-- 
          - #TOURNAMENT
        -->

        <section class="tournament" id="giveaway">
          <div class="container">

            <div class="tournament-content">

              <p class="tournament-subtitle">Check out our</p>

              <h2 class="h3 tournament-title">Giveaways</h2>

              <p class="tournament-text">
                We do many giveaways of money, nitro, bot shop, GTA cash, FiveM cash etc.
              </p>

              <a href="https://discord.gg/ZkJQVWSXx" class="btn btn-primary">Join Giveaways</a>

            </div>

            <div class="tournament-prize">

              <h2 class="h3 tournament-prize-title">Prize</h2>

              <data value="5">20 Milions for GTA V online</data>

              <figure>
                 
                <img src=" ../assets/images/prize-img.png" alt="Prize image">
              </figure>

            </div>

            <div class="tournament-winners">

              <h2 class="h3 tournament-winners-title">Last winners</h2>

              <ul class="tournament-winners-list">

                <li>
                  <div class="winner-card">

                    <figure class="card-banner">
                       <div id="gaw">
                      </div>
                    </figure>

                    <h3 class="h5 card-title">1st place</h3>

                  </div>
                </li>

              </ul>

            </div>

          </div>
        </section>





        <!-- 
          - #GALLERY
        -->

        <section class="gallery">
            
          <div class="container">
<h2 class="h2 section-title">Features</h2>
            <ul class="gallery-list has-scrollbar">

              <li>
                <figure class="gallery-item">
                  <img src="../assets/images/aromax_api.svg" alt="Aromax API">
                </figure>
              </li>

              <li>
                <figure class="gallery-item">
                  <img src="../assets/images/aromax_support.svg" alt="Aromax Support">
                </figure>
              </li>

              <li>
                <figure class="gallery-item">
                  <img src="../assets/images/aromax_cdesign.svg" alt="Costum Design Bot">
                </figure>
              </li>

              <li>
                <figure class="gallery-item">
                  <img src="../assets/images/aromax_bteam.svg" alt="Build your Team">
                </figure>
              </li>

            </ul>

          </div>
        </section>
        
        <nav>
          <ul>
            <div class="menu-select">
            <li><a>Select option</a>
              <ul>
                <li><a href="a">2 Millions - 0.50€</a></li>
                <li><a href="a">Drop 2</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
              </ul>
            </li>
          </div>
          </ul>
        </nav>

        <nav>
          <ul>
            <div class="menu-select2">
            <li><a>Select option</a>
              <ul>
                <li><a href="a">Drop 1</a></li>
                <li><a href="a">Drop 2</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
              </ul>
            </li>
          </div>
          </ul>
        </nav>

        <nav>
          <ul>
            <div class="menu-select3">
            <li><a>Select option</a>
              <ul>
                <li><a href="a">Drop 1</a></li>
                <li><a href="a">Drop 2</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
              </ul>
            </li>
          </div>
          </ul>
        </nav>

        <nav>
          <ul>
            <div class="menu-select4">
            <li><a>Select option</a>
              <ul>
                <li><a href="#gears"> caca</a></li>
                <li><a href="a">Drop 2</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
                <li><a href="a">Drop 3</a></li>
              </ul>
            </li>
          </div>
          </ul>
        </nav>

        <!-- 
          - #GEARS
        -->

        <section class="gears" id="gears">
          <div class="container">

            <h2 class="h2 section-title">check our shop</h2>

            <ul class="gears-list">

              <li>
                <div class="gears-card">

                  <div class="card-banner">

                    <a href="a">
                      <img src="../assets/images/mee6.png" alt="Ipplo Music">
                    </a>

                    <button class="share">
                      <ion-icon name="share-social"></ion-icon>
                    </button>

                    <div class="card-time-wrapper">
                      <ion-icon name="time-outline"></ion-icon>

                      <span>In 7 days</span>
                    </div>

                  </div>

                  <div class="card-content">

                    <div class="card-title-wrapper">

                      <h3 class="h3 card-title">NOAuth BOT</h3>

                      <p class="card-subtitle">1 month</p>

                    </div>

                    <div class="card-prize">$4</div>

                  </div>

                  <div class="card-actions">

                    <button class="btn btn-primary">
                      <ion-icon name="add-outline"></ion-icon>

                      <span>Add to cart</span>
                    </button>

                  </div>

                </div>

              <li>
                <div class="gears-card">

                  <div class="card-banner">

                    <a href="a">
                      <img src=" ../assets/images/rythm.png" alt="Controller">
                    </a>

                    <button class="share">
                      <ion-icon name="share-social"></ion-icon>
                    </button>

                    <div class="card-time-wrapper">
                      <ion-icon name="time-outline"></ion-icon>

                      <span>In 4 days</span>
                    </div>

                  </div>

                  <div class="card-content">

                    <div class="card-title-wrapper">

                      <h3 class="h3 card-title">GTA CASH</h3>

                      <p class="card-subtitle">Source Code</p>

                    </div>

                    <div class="card-prize"></div>

                  </div>
                  

                  <div class="card-actions">

                    <button class="btn btn-primary">
                      <ion-icon name="add-outline"></ion-icon>

                      <span>Add to cart</span>
                    </button>

                  </div>

                </div>
              </li>

              <li>
                <div class="gears-card">

                  <div class="card-banner">

                    <a href="a">
                      <img src=" ../assets/images/rythm.png" alt="Controller">
                    </a>

                    <button class="share">
                      <ion-icon name="share-social"></ion-icon>
                    </button>

                    <div class="card-time-wrapper">
                      <ion-icon name="time-outline"></ion-icon>

                      <span>In 4 days</span>
                    </div>

                  </div>

                  <div class="card-content">

                    <div class="card-title-wrapper">

                      <h3 class="h3 card-title">Rythm Bot</h3>

                      <p class="card-subtitle">Source Code</p>

                    </div>

                    <div class="card-prize">$29</div>

                  </div>

                  <div class="card-actions">

                    <button class="btn btn-primary">
                      <ion-icon name="add-outline"></ion-icon>

                      <span>Add to cart</span>
                    </button>

                  </div>

                </div>
              </li>


              <li>
                <div class="gears-card">

                  <div class="card-banner">

                    <a href="a">
                      <img src=" ../assets/images/ticket.png" alt="Gaming mask">
                    </a>

                    <button class="share">
                      <ion-icon name="share-social"></ion-icon>
                    </button>

                    <div class="card-time-wrapper">
                      <ion-icon name="time-outline"></ion-icon>

                      <span>In 4 days</span>
                    </div>

                  </div>

                  <div class="card-content">

                    <div class="card-title-wrapper">

                      <h3 class="h3 card-title">Ticket Bot</h3>

                      <p class="card-subtitle">Source Code</p>

                    </div>

                    <div class="card-prize">$15</div>

                  </div>

                  <div class="card-actions">

                    <button class="btn btn-primary">
                      <ion-icon name="add-outline"></ion-icon>

                      <span>Add to cart</span>
                    </button>

                  </div>

                </div>
              </li>

            </ul>

          </div>
        </section>





        <!-- 
           #NEWSLETTER
        -->
        <section class="newsletter">
          <div class="container">

            <div class="newsletter-card">

              <div class="newsletter-content">
                <figure class="newsletter-img">
                  <img src=" ../assets/images/newsletter-img.png" alt="Newsletter image">
                </figure>

                <h2 class="h2 newsletter-title">Subscribe to our newsletter</h2>
              </div>

              <form action="" class="newsletter-form">
                <input type="email" name="email" required placeholder="Your Email Address" class="input-field">

                <button type="submit" class="btn btn-secondary">Subscribe</button>
              </form>

            </div>

          </div>
        </section>

      </div>

    </article>
  </main>

