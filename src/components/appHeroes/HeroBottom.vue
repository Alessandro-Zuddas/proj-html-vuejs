<script>
export default {

    name: "HeroBottom",

    data() {
        return {
        
        }
    }
}
</script>

<template>
  <!-- Hero Bottom Top -->
  <div class="container">
    <!-- Hero Bottom header -->
    <h2 class="main-title">Trusted Partners</h2>
    <hr>
    <p class="desc-text">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum saepe ab quis accusantium repellendus aspernatur repudiandae, <br> maxime perspiciatis deserunt impedit ipsam magni quae placeat dolor.
    </p>
    <!-- /Hero Bottom header -->

    <!-- Trusted partners section -->
    <div class="container-md">
      <div class="row">
        <div class="column">
          <img class="partner-img" src="../../assets/img/home-logo11-219096700-320x202.png" alt="">
        </div>
        <div class="column">
          <img class="partner-img" src="../../assets/img/home-logo10-219096700-320x202.png" alt="">
        </div>
        <div class="column">
          <img class="partner-img" src="../../assets/img/home-logo2-219096700-320x202.png" alt="">
        </div>
        <div class="column">
          <img class="partner-img" src="../../assets/img/home-logo1-219096700-320x202.png" alt="">
        </div>
        <div class="column">
          <img class="partner-img" src="../../assets/img/home-logo9-219096700-320x202.png" alt="">
        </div>
      </div>
    </div>
    <!-- /Trusted partners section -->
  </div>
  <!-- /Hero Bottom Top -->

  <!-- Hero Bottom Down -->
  <div class="container cont-two">
    <div class="container-sm">
      <div class="row-two">
        <!-- Hero Left -->
        <div class="col-big">
          <h2 class="hero-title-two">Building Inspiring New Spaces</h2>
          <hr class="hero-bt-line">
          <p class="hero-two-text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus magnam, distinctio itaque architecto cupiditate consequuntur labore, minus quos quasi saepe adipisci vitae error.
          </p>
        </div>
        <!-- /Hero Left -->
        <!-- Hero right -->
        <div class="col-small">
          <button class="hero-btn">GET A FREE QUOTE!</button>
          <small class="free-trial-text">Only takes a few seconds!</small>
        </div>
        <!-- /Hero right -->
      </div>
    </div>
  </div>
  <!-- /Hero Bottom Down -->
</template>

<style scoped>

/* Hero Bottom Top */

.container{
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 3.125rem;
}

.main-title{
  color: var(--titles-color);
  padding-bottom: 1.25rem;
}

hr{
  width: 8%;
  height: .125rem;
  background-color: #fed03d;
  border: none;
}

.desc-text{
  color: var(--titles-color);
  text-align: center;
  margin-top: 1.5625rem;
  margin-bottom: 2.5rem;
}

.row{
  display: flex;
  justify-content: space-between;
  text-align: center;
  width: 100%;
  margin-top: .625rem;
}

.column{
  width: calc(100% / 5 - 10px);
  margin: 0 .625rem;
  margin-bottom: 3.125rem;
}

.partner-img{
  max-width: 13.75rem;
}

.partner-img:hover{
  transform: scale(1.1);
}

/* /Hero Bottom Top */

/* Hero Bottom Down */

.cont-two{
  padding: 9.375rem 0;
  background-image: url(../../assets/img/about-call-to-action-57862405.jpg);
  background-position: bottom;
  background-size: cover;
}

.row-two{
  display: flex;
  width: 100%;
}

.col-big{
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 70%;
  padding: .625rem .625rem;
}

.col-small{
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: 30%;
  padding: .625rem .625rem;
}

.hero-title-two{
  color: white;
  padding-bottom: 1.25rem;
}

.hero-bt-line{
  width: 20%;
  background-color: rgba(255, 225, 0, 0.8);
  margin: .625rem 0;
  margin-bottom: 1.5625rem;
}

.hero-two-text{
  color: white;
}

.hero-btn{
  color: var(--titles-color);
  background-color: var(--first-color);
  border: none;
  padding: .625rem 1.5625rem;
  margin-bottom: .3125rem;
  cursor: pointer;
}

.hero-btn:hover{
  color: white;
  background-color: var(--second-color);
}

.free-trial-text{
  color: white;
  font-size: .75rem;
}

/* /Hero Bottom Down */

</style>