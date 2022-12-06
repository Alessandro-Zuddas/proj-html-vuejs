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
    <h2 class="main-title">Explore Recent Work</h2>
    <hr>
    <p class="desc-text">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum saepe ab quis accusantium repellendus aspernatur repudiandae, <br> maxime perspiciatis deserunt impedit ipsam magni quae placeat dolor.
    </p>
    <!-- /Main Middle One Header -->

    <!-- Projects Images -->
    <div class="container-sm">
      <div class="row">
        <div class="column">
          <img class="project-img" src="../../assets/img/project1-featured-294276386-400x400.jpg" alt="Project One Image">
        </div>
        <div class="column">
          <img class="project-img" src="../../assets/img/project2-featured-15013609-400x400.jpg" alt="Project One Image">
        </div>
        <div class="column">
          <img class="project-img" src="../../assets/img/project3-featured-189023420-400x400.jpg" alt="Project One Image">
        </div>
      </div>
    </div>
    <!-- /Projects Images -->

    <div class="container-sm sm-two">
      <div class="column">
        <hr class="all-projects-line">
      </div>
      <div class="column">
        <h5 class="all-projects-text">VIEW ALL PROJECTS</h5>
      </div>
      <div class="column">
        <hr class="all-projects-line"> 
      </div>
    </div>

    <div class="container bg-variant">
      <!-- Main Middle Two Header -->
      <div class="container-sm sm-three">
        <h2 class="main-title">Our Core Values</h2>
        <hr>
        <p class="desc-text">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum saepe ab quis accusantium repellendus aspernatur repudiandae, <br> maxime perspiciatis deserunt impedit ipsam magni quae placeat dolor.
        </p>
        <!-- /Main Middle Two Header -->

        <!-- Company Highligts -->
        <div class="row">
          <!-- High One -->
          <div class="column-sm">
              <div class="highligts high-one">
                <i class="fa-sharp fa-solid fa-house high-icon"></i>
              </div>
              <strong class="high-title">
                Great Services
              </strong>
              <hr class="high-line">
              <p class="high-text">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Amet consectetur adipisicing elit.
              </p>
          </div>
          <!-- /High One -->
          <!-- High Two -->
          <div class="column-sm">
              <div class="highligts high-two">
                <i class="fa-solid fa-gear  high-icon"></i>
              </div>
              <strong class="high-title">
                Highest Standards
              </strong>
              <hr class="high-line">
              <p class="high-text">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Amet consectetur adipisicing elit.
              </p>
          </div>
          <!-- /High Two -->
          <!-- High Three -->
          <div class="column-sm">
              <div class="highligts high-three">
                <i class="fa-solid fa-users high-icon"></i>
              </div>
              <strong class="high-title">
                Professional Team
              </strong>
              <hr class="high-line">
              <p class="high-text">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Amet consectetur adipisicing elit.
              </p>
          </div>
          <!-- /High Three -->
          <!-- High Four -->
          <div class="column-sm">
              <div class="highligts high-four">
                <i class="fa-solid fa-lightbulb high-icon"></i>
              </div>
              <strong class="high-title">
                Creative Solutions
              </strong>
              <hr class="high-line">
              <p class="high-text">
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Amet consectetur adipisicing elit.
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
  color: var(--titles-color);
  padding-bottom: .625rem;
}

hr{
  width: 6.25rem;
  height: .125rem;
  background-color: #fed03d;
  border: none;
}

.desc-text{
  text-align: center;
  margin-top: 1.5625rem;
  margin-bottom: 2.5rem;
}

.project-img{
  max-width: 18.75rem;
}

.row{
  display: flex;
  justify-content: space-between;
  width: 100%;
}

.column{
  width: calc(100% / 3);
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
  color: var(--titles-color);
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
  background-color: #f5f5f5;
}

.column-sm{
  display: flex;
  flex-direction: column;
  align-items: center;
  width: calc(96% / 4);
  text-align: center;
  margin-top: 1.25rem;
}

.highligts{
  display: flex;
  justify-content: center;
  align-items: center;
  border: none;
  border-radius: 50%;
  aspect-ratio: 1;
}

.high-one{
  background-color: #4ea4a5;
}

.high-two{
  background-color: #4ea4a5;
}

.high-three{
  background-color: #f6722a;
}

.high-four{
  background-color: #a7cf47;
}

.high-icon{
  color: white;
  font-size: 2.1875rem;
  padding: 2.1875rem 2.1875rem;
}

.high-title{
  color: var(--titles-color);
  margin-top: .625rem;
  margin-bottom: .625rem;
}

.high-line{
  width: 20%;
}

.high-text{
  color: var(--titles-color);
  font-size: .875rem;
  margin-top: 1.25rem;
}

/* /Company Highligts */

</style>