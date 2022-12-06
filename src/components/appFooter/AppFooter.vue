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
        <div>Logo</div>
        <p class="footer-text">
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Autem similique voluptatum quis doloribus eum labore laboriosam nemo explicabo et quaerat cumque nostrum, quod eius in, rem consequatur mollitia architecto distinctio?
        </p>
        <button class="learn-more-btn">Learn More</button>
      </div>
      <!-- /Footer Col One -->
      <!-- Footer Col two -->
      <div class="column">
        <strong>Titolo colonna</strong>
        <div class="tweet-container">
          <img class="profile-img" src="https://via.placeholder.com/50" alt="">
          <div class="tweet-text-container">
            <strong>ThemeFusion</strong>
            <small class="account-name">@Theme_Fusion</small>
            <small>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Est ex, neque saepe recusandae nam dolore deserunt esse molestiae illo aspernatur fugit explicabo sapiente quaerat velit ratione quam dignissimos. Aliquam, officiis.
            </small>
            <img class="tweet-img" src="https://via.placeholder.com/300x150" alt="">
            <div class="icons-container">
              <div>
                Icon
                Icon
              </div>
              <div>
                Icon
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- /Footer Col two -->
      <!-- Footer Col three -->
      <div class="column col-three">
        <strong>Titolo colonna</strong>
        <div class="icon-plus-text">
          Icon
          <small class="col-three-text">Testo di prova</small>
        </div>
        <div class="icon-plus-text">
          Icon
          <small class="col-three-text">Testo di prova</small>
        </div>
        <div class="icon-plus-text">
          Icon
          <small class="col-three-text">Testo di prova</small>
        </div>
        <div class="icon-plus-text">
          Icon
          <small class="col-three-text">Testo di prova</small>
        </div>
        <div class="icon-plus-text">
          Icon
          <small class="col-three-text">Testo di prova</small>
        </div>
        <div class="icon-plus-text">
          Icon
          <small class="col-three-text">Testo di prova</small>
        </div>
      </div>
      <!-- /Footer Col three -->
      <!-- Footer Col Four -->
      <div class="column col-four">
        <strong>Titolo colonna</strong>
        <img class="find-us-img" src="https://via.placeholder.com/250x250" alt="">
      </div>
      <!-- /Footer Col Four -->
    </div>
    <!-- /Footer Top -->

    <!-- Footer Bottom -->
    <div class="container cont-two">
      <small>
        Copy text Lorem ipsum dolor, sit amet consectetur adipisicing elit | Lorem ipsum dolor sit amet consectetur adipisicing elit.
      </small>
      <div class="icons-container-bt">
        Icon
        Icon
        Icon
        Icon
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
  width: calc(100% / 4 - .625rem);
  margin: 0 1.25rem;
}

.footer-text{
  margin: .625rem 0;
}

.learn-more-btn{
  padding: .3125rem .625rem;
}

.tweet-container{
  display: flex;
}

.profile-img{
  max-height: 3.125rem;
  margin-top: .625rem;
  margin-right: .3125rem;
}

.tweet-text-container{
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin-top: .5rem;
}

.account-name{
  margin-bottom: .3125rem;
}

.tweet-img{
  max-width: 18.75rem;
  max-height: 9.375rem;
  margin-top: .625rem;
}

.icons-container{
  display: flex;
  justify-content: space-between;
}

.col-three{
  margin-left: 3.125rem;
}

.icon-plus-text{
  display: flex;
  align-items: center;
  margin-bottom: .625rem;
  margin-top: .625rem;
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
  max-width: 15.625rem;
  max-height: 15.625rem;
}

/* /Footer top */

/* Footer bottom */

.cont-two{
  display: flex;
  justify-content: space-between;
  padding: 1.5625rem 2.5rem;  
  background-color: black;
  color: lightgray;
}

.icons-container-bt{
  margin-right: 3.125rem;
}

/* /Footer bottom */
</style>