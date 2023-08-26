

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
    <!-- 
      - favicon link
    -->
    <link rel="shortcut icon" href="../assets/favicon.svg" type="../assets/images/svg+xml">
  
    <!-- 
      - custom css link
    -->
    <link rel="stylesheet" href="./static/assets/css/style.css">
    <link rel="stylesheet" href="./static/assets/css/dashboard.css">
    <link rel="stylesheet" href="./static/assets/css/profile.css">  
    <!-- 
      - google font link
    -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link
      href="https://fonts.googleapis.com/css2?family=Oswald:wght@300;400;500;600;700&family=Poppins:wght@400;500;700&display=swap"
      rel="stylesheet">
  </head>
  

  
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
  
  
             <!--  <% if(is_logged) {%>-->
                   
                <a href="/profile" style="color: #FFFFFF;"><!--<%= user.username %>#<%= user.discriminator %>--></a>
          <!--    <%} else {%>-->
      <img src="../assets/images/logo.svg">
      <!--  <%}%> -->
          </button>
            <button class="nav-close-btn" data-nav-close-btn>
              <ion-icon name="close-outline"></ion-icon>
            </button>
  
          </div>
  
          <ul class="navbar-list">
  
            <li>
              <a href="http://localhost:5173/" class="navbar-link">Home</a>
            </li>
  
            <li>
              <a href="http://localhost:5173/#about" class="navbar-link">About</a>
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
               <!-- <% if(is_logged) {%> -->
                <img src="https://cdn.discordapp.com/avatars/"> <!--<%= user.id %>/<%= user.avatar %>.png?size=512%>--> 
                <!-- <%} else {%>-->
    <ion-icon name="log-in-outline"></ion-icon>
               <!--   <%}%> -->
              
            </div>
  
             <!--  <% if(is_logged) {%>-->
                <span><!--<%= user.username %>#<%= user.discriminator %>--></span>
           <!--   <%} else {%>-->
    <span><a href="/auth/login" style="color: #FFFFFF;">Log-in</a></span>
               <!--   <%}%>-->
          </button>
  
        </div>
  
      </div>
  
    </header>

    <slot></slot>

  <!-- 
    - #FOOTER
  -->

  <footer>

    <div class="footer-top">
      <div class="container">

        <div class="footer-brand-wrapper">

          <a href="a" class="logo">
            <img src=" ../assets/images/logo.svg" alt="GameX logo">
          </a>

          <div class="footer-menu-wrapper">

            <ul class="footer-menu-list">

              <li>
                <a href="#hero" class="footer-menu-link">Home</a>
              </li>

              <li>
                <a href="#about" class="footer-menu-link">About</a>
              </li>


              <li>
                <!--<% if(is_logged) {%>-->
             <a href="/auth/logout" class="footer-menu-link">Logout</a>
           <!-- <%} else {%>-->
 <a href="/auth/login" class="footer-menu-link">Login</a>
             <!--   <%}%>-->
              </li>

            </ul>

            <div class="footer-input-wrapper">
<!--               <input type="text" name="message" required placeholder="Find Here Now" class="footer-input"> -->
                    
<!--                   <% if(is_logged) {%>
                      <center>
             <a href="/auth/logout" class="footer-menu-link">Logout</a>
            <%} else {%>
 <a href="/auth/login" class="footer-menu-link">Login</a>
                <%}%>
          </center> -->

<!--               <button class="btn btn-primary">
                <ion-icon name="search-outline"></ion-icon>
              </button> -->
            </div>

          </div>

        </div>

        <div class="footer-quicklinks">

          <ul class="quicklink-list">

            <li>
              <a href="a" class="quicklink-item">Faq</a>
            </li>

            <li>
              <a href="a" class="quicklink-item">Help center</a>
            </li>

            <li>
              <a href="a" class="quicklink-item">Terms of use</a>
            </li>

            <li>
              <a href="a" class="quicklink-item">Privacy</a>
            </li>

          </ul>

          <ul class="footer-social-list">

            <li>
              <a href="a" class="footer-social-link">
                <ion-icon name="logo-discord"></ion-icon>
              </a>
            </li>

            <li>
              <a href="a" class="footer-social-link">
                <ion-icon name="logo-twitch"></ion-icon>
              </a>
            </li>

            <li>
              <a href="a" class="footer-social-link">
                <ion-icon name="logo-xbox"></ion-icon>
              </a>
            </li>

            <li>
              <a href="a" class="footer-social-link">
                <ion-icon name="logo-youtube"></ion-icon>
              </a>
            </li>

          </ul>

        </div>

      </div>
    </div>

    <div class="footer-bottom">
      <div class="container">
        <p class="copyright">
          Copyright &copy; 2022 <a href="a">Aromax</a>. all rights reserved
        </p>

        <figure class="footer-bottom-img">
          <img src=" ../assets/images/footer-bottom-img.png" alt="Online payment companies logo">
        </figure>
      </div>
    </div>

  </footer>
  
    <!-- 
    - #GO TO TOP
  -->

  <a href="#top" class="btn btn-primary go-top" data-go-top>
    <ion-icon name="chevron-up-outline"></ion-icon>
  </a>


  <!-- 
    - custom js link
  -->
  <!-- <script src="/js/script.js"></script> -->

  <!-- 
    - ionicon link
  -->
  <!--<script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>-->




