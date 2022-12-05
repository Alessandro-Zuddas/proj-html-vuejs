<script>
export default {

    name: "MainMiddle",

    data() {
        return {
        
        }
    }
}
</script>

<template>
  
  <div class="container">
    <!-- Main Middle One Header -->
    <h2 class="main-title">Titolo main middle one</h2>
    <hr>
    <p class="desc-text">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum saepe ab quis accusantium repellendus aspernatur repudiandae, <br> maxime perspiciatis deserunt impedit ipsam magni quae placeat dolor.
    </p>
    <!-- /Main Middle One Header -->

    <!-- Projects Images -->
    <div class="container-sm">
      <div class="row">
        <div class="column">
          <img src="https://via.placeholder.com/200x200" alt="">
        </div>
        <div class="column">
          <img src="https://via.placeholder.com/200x200" alt="">
        </div>
        <div class="column">
          <img src="https://via.placeholder.com/200x200" alt="">
        </div>
      </div>
    </div>
    <!-- /Projects Images -->

    <div class="container-sm sm-two">
      <div class="column">
        <hr class="all-projects-line">
      </div>
      <div class="column">
        <h5 class="all-projects-text">Prova testo</h5>
      </div>
      <div class="column">
        <hr class="all-projects-line"> 
      </div>
    </div>

    <div class="container bg-variant">
      <!-- Main Middle Two Header -->
      <div class="container-sm sm-three">
        <h2 class="main-title">Titolo main middle two</h2>
        <hr>
        <p class="desc-text">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum saepe ab quis accusantium repellendus aspernatur repudiandae, <br> maxime perspiciatis deserunt impedit ipsam magni quae placeat dolor.
        </p>
        <!-- /Main Middle Two Header -->

        <!-- Company Highligts -->
        <div class="row">
          <!-- High One -->
          <div class="column-sm">
              <div class="highligts">
                Icon
              </div>
              <strong class="high-title">
                High title
              </strong>
              <hr class="high-line">
              <p class="high-text">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
              </p>
          </div>
          <!-- /High One -->
          <!-- High Two -->
          <div class="column-sm">
              <div class="highligts">
                Icon
              </div>
              <strong class="high-title">
                High title
              </strong>
              <hr class="high-line">
              <p class="high-text">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
              </p>
          </div>
          <!-- /High Two -->
          <!-- High Three -->
          <div class="column-sm">
              <div class="highligts">
                Icon
              </div>
              <strong class="high-title">
                High title
              </strong>
              <hr class="high-line">
              <p class="high-text">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
              </p>
          </div>
          <!-- /High Three -->
          <!-- High Four -->
          <div class="column-sm">
              <div class="highligts">
                Icon
              </div>
              <strong class="high-title">
                High title
              </strong>
              <hr class="high-line">
              <p class="high-text">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit.
              </p>
          </div>
          <!-- /High Four -->
        </div>
        <!-- /Company Highligts -->
      </div>
    </div>
  </div>

</template>

<style scoped>

/* Projects Images */

.container{
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 3.125rem;
}

.main-title{
  padding-bottom: .625rem;
}

hr{
  width: 5%;
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
}

.column{
  width: calc(96% / 3);
  text-align: center;
}

.sm-two{
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 1.25rem;
  margin-bottom: 2.5rem;
}

.all-projects-text{
  padding: .9375rem 0;
}

.all-projects-line{
  width: 100%;
  background-color: lightgray;
}

/* /Projects Images */

/* Company Highligts */
.sm-three{
  display: flex;
  flex-direction: column;
  align-items: center;
}

.bg-variant{
  background-color: lightgray;
}

.column-sm{
  display: flex;
  flex-direction: column;
  align-items: center;
  width: calc(98% / 4);
  text-align: center;
  margin-top: 1.25rem;
}

.highligts{
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 1.5625rem 1.5625rem;
  border: .0625rem solid black;
  border-radius: 50%;
  aspect-ratio: 1;
}

.high-title{
  margin-top: .625rem;
  margin-bottom: .625rem;
}

.high-line{
  width: 20%;
}

.high-text{
  margin-top: .625rem;
}

/* /Company Highligts */

</style>