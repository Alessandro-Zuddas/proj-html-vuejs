<script>
export default {

    name: "HeroBottom",

    data() {
        return {
        title: 'Hero Bottom'
        }
    }
}
</script>

<template>
  <!-- Hero Bottom Top -->
  <div class="container">
    <!-- Hero Bottom header -->
    <h2 class="main-title">Titolo hero bottom</h2>
    <hr>
    <p class="desc-text">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum saepe ab quis accusantium repellendus aspernatur repudiandae, <br> maxime perspiciatis deserunt impedit ipsam magni quae placeat dolor.
    </p>
    <!-- /Hero Bottom header -->

    <!-- Trusted partners section -->
    <div class="container-sm">
      <div class="row">
        <div class="column">
          <img src="https://via.placeholder.com/120" alt="">
        </div>
        <div class="column">
          <img src="https://via.placeholder.com/120" alt="">
        </div>
        <div class="column">
          <img src="https://via.placeholder.com/120" alt="">
        </div>
        <div class="column">
          <img src="https://via.placeholder.com/120" alt="">
        </div>
        <div class="column">
          <img src="https://via.placeholder.com/120" alt="">
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
          <h2>Titolo Hero two</h2>
          <hr class="hero-bt-line">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus magnam, distinctio itaque architecto cupiditate consequuntur labore, minus quos quasi saepe adipisci vitae error.
          </p>
        </div>
        <!-- /Hero Left -->
        <!-- Hero right -->
        <div class="col-small">
          <button class="hero-btn">Get a free quote</button>
          <small class="free-trial-text">Testo segnaposto di prova</small>
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
  padding-bottom: .625rem;
}

hr{
  width: 12%;
  height: .125rem;
  background-color: #fed03d;
  border: none;
}

.desc-text{
  text-align: center;
  margin-top: 1.5625rem;
  margin-bottom: 2.5rem;
}

.row{
  display: flex;
  justify-content: space-between;
  width: 100%;
  margin-top: .625rem;
}

.column{
  width: calc(100% / 5 - 10px);
  margin: 0 .625rem;
  margin-bottom: 3.125rem;
}

/* /Hero Bottom Top */

/* Hero Bottom Down */

.cont-two{
  padding: 3.125rem 0;
  background-color: beige;
}

.row-two{
  display: flex;
  width: 100%;
}

.col-big{
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

.hero-bt-line{
  width: 20%;
  background-color: rgba(255, 225, 0, 0.8);
  margin: .625rem 0;
}

.hero-btn{
  padding: .3125rem .9375rem;
  margin-bottom: .3125rem;
}

.free-trial-text{
  font-size: .75rem;
}

/* /Hero Bottom Down */

</style>