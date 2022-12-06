<script>
export default {

    name: "AppFooter",

    data() {
        return {
        
        }
    }
}
</script>

<template>

  <!-- Footer Top -->
  <div class="container">
    <div class="row">
      <!-- Footer Col One -->
      <div class="column">
        <img src="../../assets/img/footer-logo.png" alt="">
        <p class="footer-text">
          We are specialists in the construction of unique and exclusive properties. Our work inspires. We pride ourselves on delivering outstanding quality and design for leading clients across the world
        </p>
        <button class="learn-more-btn">LEARN MORE</button>
      </div>
      <!-- /Footer Col One -->
      <!-- Footer Col two -->
      <div class="column">
        <img class="twitter-img" src="../../assets/img/image (1).svg" alt="">
        <strong class="col-title">LATEST TWEETS</strong>
        <div class="tweet-container">
          <img class="profile-img" src="../../assets/img/3a74ce3d0532b7773b174c45ca3bd05a_normal.png" alt="">
          <div class="tweet-text-container">
            <strong>ThemeFusion</strong>
            <small class="account-name">@Theme_Fusion</small>
            <small>
              Do you need sublime WordPress hosting for your next website? Take advantage of exclusive partner offers that we have secured just for you, & launch your site in seconds width <span class="hastag">#avada</span> on WP Engine hosting & get 30% Off this Black Friday <a href="#">bit.ly/3kjLLE2</a> <span class="hastag">#BlackFriday2022</span>
            </small>
            <img class="tweet-img" src="../../assets/img/En2TRxLW4AEiWUN.jpeg" alt="">
            <div class="icons-container">
              <div>
                <a href="#"><i class="fa-regular fa-heart tweet-icon"></i></a>
                <a href="#"><i class="fa-solid fa-share-from-square tweet-icon"></i></a>
              </div>
              <div>
                <small class="tweet-icon">22h</small>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- /Footer Col two -->
      <!-- Footer Col three -->
      <div class="column col-three">
        <strong class="col-title">CONTACT US TODAY</strong>
        <div class="icon-plus-text">
          <i class="fa-sharp fa-solid fa-globe contact-us-icon"></i>
          <small class="col-three-text">
            Corporate Location <br>
            1600 Amphitheatre Parkway <br>
            London WC1 1BA
          </small>
        </div>
        <div class="icon-plus-text">
          <i class="fa-solid fa-house contact-us-icon"></i>
          <small class="col-three-text">
            Residential Location <br>
            9521 Broadsberry Avenue <br>
            Paddington RC7 9ZA
          </small>
        </div>
        <div class="icon-plus-text">
          <i class="fa-solid fa-phone-flip contact-us-icon-two"></i>
          <small class="col-three-text">1.800.458.556 / 1.800.532.2112</small>
        </div>
        <div class="icon-plus-text">
          <i class="fa-regular fa-envelope contact-us-icon-two"></i>
          <small class="col-three-text">info@your-domain.com</small>
        </div>
        <div class="icon-plus-text">
          <i class="fa-regular fa-clock contact-us-icon-two"></i>
          <small class="col-three-text">Monday - Friday: 9:00 AM - 6:00 PM</small>
        </div>
        <div class="icon-plus-text">
          <i class="fa-regular fa-clock contact-us-icon-two"></i>
          <small class="col-three-text">Saturday - Sunday: 9:00 AM - 12:00 PM</small>
        </div>
      </div>
      <!-- /Footer Col three -->
      <!-- Footer Col Four -->
      <div class="column col-four">
        <strong class="col-title">FIND US</strong>
        <img class="find-us-img" src="../../assets/img/construction_map_pin.png" alt="">
      </div>
      <!-- /Footer Col Four -->
    </div>
    <!-- /Footer Top -->

    <!-- Footer Bottom -->
    <div class="container cont-two">
      <small class="footer-bt-text">
        COPYRIGHT 2012 - 2015 AVADA THEME BY <strong>THEME FUSIN</strong> | ALL RIGHTS RESERVED | POWERED BY <strong>WORDPRESS</strong>
      </small>
      <div class="icons-container-bt">
        <a class="social-icons" href="#"><i class="fa-brands fa-facebook-f"></i></a>
        <a class="social-icons" href="#"><i class="fa-brands fa-twitter"></i></a>
        <a class="social-icons" href="#"><i class="fa-brands fa-youtube"></i></a>
        <a class="social-icons" href="#"><i class="fa-brands fa-instagram"></i></a>
      </div>
    </div>
    <!-- Footer Bottom -->
  </div>

</template>

<style scoped>

/* Footer top */

.row{
  display: flex;
  justify-content: space-between;
  width: 100%;
  background-color: #1e1e1e;
  padding: 1.5625rem 1.5625rem;
  color: lightgray;
}

.column{
  position: relative;
  width: calc(100% / 4 - .625rem);
  margin: 0 1.25rem;
}

.footer-text{
  color: var(--titles-color);
  margin: 1.5625rem 0;
}

.learn-more-btn{
  color: var(--titles-color);
  background-color: var(--first-color);
  border: none;
  padding: .5rem 1.25rem;
  cursor: pointer;
}

.col-title{
  color: var(--first-color);
  margin-bottom: 1.25rem;
}

.tweet-container{
  display: flex;
  margin-top: 1.25rem;
}

.twitter-img{
  position: absolute;
  top: 10%;
  right: 2%;
  width: 1.25rem;
}

.profile-img{
  max-height: 3.125rem;
  margin-top: .625rem;
  margin-right: .3125rem;
  border-radius: 50%;
}

.tweet-text-container{
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin-top: .5rem;
}

.hastag{
  color: #2a71a7;
}

a{
  color: #2a71a7;
  text-decoration: none;
}

.account-name{
  margin-bottom: .3125rem;
}

.tweet-img{
  max-width: 21.875rem;
  max-height: 12.5rem;
  margin-top: .625rem;
}

.icons-container{
  display: flex;
  justify-content: space-between;
}

.tweet-icon{
  padding-top: .3125rem;
  padding-right: .625rem;
  color: var(--titles-color);
}

.col-three{
  margin-left: 3.125rem;
}

.icon-plus-text{
  display: flex;
  color: var(--titles-color);
  margin-top: 1.25rem;
}

.contact-us-icon{
  padding-top: .625rem;
}

.contact-us-icon-two{
  padding-top: .375rem;
}


.col-three-text{
  margin-left: .625rem;
  margin-top: .3125rem;
}

.col-four{
  display: flex;
  flex-direction: column;
}

.find-us-img{
  margin-top: .625rem;
  max-width: 18.75rem;
  max-height: 15.625rem;
}

/* /Footer top */

/* Footer bottom */

.cont-two{
  display: flex;
  justify-content: space-between;
  padding: 1.5625rem 2.5rem;  
  background-color: black;
  color: var(--titles-color);
}

.footer-bt-text{
  font-size: .75rem;
}

.icons-container-bt{
  margin-right: 3.125rem;
}

.social-icons{
  color: var(--titles-color);
  padding: 0 .3125rem;
}

/* /Footer bottom */
</style>