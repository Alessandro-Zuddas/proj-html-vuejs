<script>
export default {

    name: "MainBottom",

    data() {
      return {
      
      }
    }
}
</script>

<template>
  <div class="container">
    <!-- Reviews -->
    <div class="row bg-variant">   
      <div class="container-xs">
        <h2 class="main-bt-title">Titolo Main Bottom</h2>
        <hr>
        <div class="review-img">
          Img
        </div>
        <p class="review-text">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Error, exercitationem doloribus.Lorem ipsum dolor sit, amet consectetur adipisicing elit. Error, exercitationem doloribus.
        </p>
        <strong class="review-user">
          Name Surname - What has done
        </strong>
        <div class="carousel-index">
          - -
        </div>
      </div>
    </div>
    <!-- /Reviews -->
  </div>

  <!-- Latest news  -->
  <div class="container cont-two">
    <!-- Latest news header -->
    <h2 class="main-title">Titolo main middle one</h2>
    <hr class="latest-news-hr">
    <p class="desc-text">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum saepe ab quis accusantium repellendus aspernatur repudiandae, <br> maxime perspiciatis deserunt impedit ipsam magni quae placeat dolor.
    </p>
    <!-- /Latest news header -->

    <!-- Latest news Images -->
    <div class="container-sm sm-two">
      <div class="row-two">
        <div class="column">
          <img src="https://via.placeholder.com/200x150" alt="">
        </div>
        <div class="column">
          <img src="https://via.placeholder.com/200x150" alt="">
        </div>
        <div class="column">
          <img src="https://via.placeholder.com/200x150" alt="">
        </div>
      </div>
    </div>
    <!-- /Latest news Images -->

    <div class="container-xs xs-three">
      <div class="column">
        <hr class="latest-news-line">
      </div>
      <div class="column">
        <h5 class="latest-news-text">Prova testo</h5>
      </div>
      <div class="column">
        <hr class="latest-news-line"> 
      </div>
    </div>
  </div>
  <!-- /Latest news  -->

</template>

<style scoped>

.container{
  /* DEBUG */
  background-color: lightgreen;
}

/* Reviews */

.container-xs{
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 1.25rem 0;
}

.main-bt-title{
  padding-top: 1.5625rem;
}

hr{
  width: 25%;
  margin: .9375rem 0;
  height: .125rem;
  background-color: #fed03d;
  border: none;
}

.review-img{
  border: .0625rem solid black;
  border-radius: 50%;
  aspect-ratio: 1;
  padding: 1.25rem 1.25rem;
  margin-bottom: 1.5625rem;
}

.review-text{
  text-align: center;
  margin-bottom: 1.5625rem;
}

.carousel-index{
  margin-top: 1.5625rem;
}

.bg-variant{
  padding: 8.5625rem 0;
  position: relative;
  overflow: hidden;
  /* DEBUG */
  background-color: lightgreen;
}

.bg-variant:before{
  content: "";
  position: absolute;
  top: -30%;
  width: 100%;
  height: 50%;
  background-color: lightgray;
  border-bottom-left-radius: 50%;
  border-bottom-right-radius: 50%; 
}

.bg-variant:after{
  content: "";
  position: absolute;
  width: 100%;
  bottom: -30%;
  height: 50%;
  background-color: white;
  border-top-left-radius: 50%;
  border-top-right-radius: 50%;
}

.container-sm{
  display: flex;
  padding: 6.25rem 0;
}

/* /Reviews */

/* Latest news */

.cont-two{
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: white;
}

.sm-two{
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 2.5rem;
  padding: 0;
}

.xs-three{
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  margin-top: 1.25rem;
  margin-bottom: 2.5rem;
}

.latest-news-hr{
  width: 15%;
}

.desc-text{
  text-align: center;
}

.row-two{
  display: flex;
  justify-content: space-between;
}

.column{
  width: calc(96% / 3);
  margin: 0 .625rem;
  text-align: center;
}

.latest-news-text{
  padding: .9375rem 0;
}

.latest-news-line{
  width: 100%;
  background-color: lightgray;
}

/* /Latest news */

</style>