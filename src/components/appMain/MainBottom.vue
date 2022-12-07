<script>
export default {

    name: "MainBottom",

    data() {
      return {
        carouselIndex: 0,
      }
    },
    methods:{
      onCarouselClick(){
        if(this.carouselIndex === 0){
          this.carouselIndex = 1;
        }else{
          this.carouselIndex = 0;
        }
      }
    }
}
</script>

<template>

  <!-- Reviews -->
  <div class="container">
    <div class="row bg-variant" @click="onCarouselClick">   
      <div class="container-xs">
        <h2 class="main-bt-title">Our Home Owners Say</h2>
        <hr>
        <img v-if="(this.carouselIndex === 0)" class="review-img" src="../../assets/img/home-testimonial-113165296.jpg" alt="Testimonial 1">
        <img v-else class="review-img" src="../../assets/img/home-testimonial-84268399.jpg" alt="Testimonial 2">
        <p v-if="(this.carouselIndex === 0)" class="review-text">
          "No man but feels more of a man in the world if he have but a bit of ground that he can call his own. However small it is on the surface, it is four thousand miles deep: and that is a very handsome property"
        </p>
        <p v-else class="review-text">
          "Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatem distinctio quod culpa perferendis quo quae ipsum id quas similique, numquam accusantium ipsa aliquid deserunt ad in pariatur laboriosam quia totam?"
        </p>
        <strong v-if="(this.carouselIndex === 0)" class="review-user">
          KATE HARRIS - NEW HOME OWNER
        </strong>
        <strong v-else class="review-user">
          HARRY SMITH - NEW HOME OWNER
        </strong>
        <div class="carousel-index">
          <div class="car-dot" :class="{ active: carouselIndex === 0 }"></div>
          <div class="car-dot" :class="{ active: carouselIndex === 1 }"></div>
        </div>
      </div>
    </div>
  </div>
  <!-- /Reviews -->

  <!-- Latest news  -->
  <div class="container cont-two">
    <!-- Latest news header -->
    <h2 class="main-title">Latest News</h2>
    <hr class="latest-news-hr">
    <p class="desc-text">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum saepe ab quis accusantium repellendus aspernatur repudiandae, <br> maxime perspiciatis deserunt impedit ipsam magni quae placeat dolor.
    </p>
    <!-- /Latest news header -->

    <!-- Latest news Images -->
    <div class="container-sm sm-two">
      <div class="row-two">
        <!-- Latest news One -->
        <div class="column img-col">
          <img class="latest-news-img" src="../../assets/img/blog-post-134132600-1200x723.jpg" alt="Blog Post One">
          <!-- On Hover Panel -->
          <div class="hover-panel">
            <div>
              <i class="fa-solid fa-link hover-panel-icons"></i>
              <i class="fa-solid fa-magnifying-glass hover-panel-icons"></i>
            </div>
            <h4 class="hover-panel-title">Redeveloping Florida's Remote Southern Coast</h4>
            <small class="hover-panel-tag">Architecture, Buildings, Construction, News</small>
          </div>
          <!-- /On Hover Panel -->
          <div class="news-col">
            <h3 class="latest-news-title">Redeveloping Florida's Remote Southern Coast</h3>
            <small class="news-date">December 15 2021</small>
            <hr class="news-hr">
            <p class="latest-news-text">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam molestias in quidem culpa molestiae delectus et soluta dolor. Totam et hic quia harum quidem temporibus, obcaecati natus error! Voluptates, ipsum.
            </p>
          </div>
        </div>
        <!-- /Latest news One -->
        <!-- Latest news two -->
        <div class="column img-col">
          <img class="latest-news-img" src="../../assets/img/blog-post-332773904-1200x723.jpg" alt="Blog Post Two">
          <!-- On Hover Panel -->
          <div class="hover-panel">
            <div>
              <i class="fa-solid fa-link hover-panel-icons"></i>
              <i class="fa-solid fa-magnifying-glass hover-panel-icons"></i>
            </div>
            <h4 class="hover-panel-title">Redeveloping Florida's Remote Southern Coast</h4>
            <small class="hover-panel-tag">Architecture, Buildings, Construction, News</small>
          </div>
          <!-- /On Hover Panel -->
          <div class="news-col">
            <h3 class="latest-news-title">How We Manage Large Construction Projects</h3>
            <small class="news-date">December 15 2021</small>
            <hr class="news-hr">
            <p class="latest-news-text">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam molestias in quidem culpa molestiae delectus et soluta dolor. Totam et hic quia harum quidem temporibus, obcaecati natus error! Voluptates, ipsum.
            </p>
          </div>
        </div>
        <!-- /Latest news two -->
        <!-- Latest news three -->
        <div class="column img-col">
          <img class="latest-news-img" src="../../assets/img/blog-post-92486644-1200x723.jpg" alt="Blog Post Three">
          <!-- On Hover Panel -->
          <div class="hover-panel">
            <div>
              <i class="fa-solid fa-link hover-panel-icons"></i>
              <i class="fa-solid fa-magnifying-glass hover-panel-icons"></i>
            </div>
            <h4 class="hover-panel-title">Redeveloping Florida's Remote Southern Coast</h4>
            <small class="hover-panel-tag">Architecture, Buildings, Construction, News</small>
          </div>
          <!-- /On Hover Panel -->
          <div class="news-col">
            <h3 class="latest-news-title">Future Proofing A Modern Home</h3>
            <small class="news-date">December 15 2021</small>
            <hr class="news-hr">
            <p class="latest-news-text">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam molestias in quidem culpa molestiae delectus et soluta dolor. Totam et hic quia harum quidem temporibus, obcaecati natus error! Voluptates, ipsum.
            </p>
          </div>
        </div>
        <!-- /Latest news three -->
      </div>
    </div>
    <!-- /Latest news Images -->

    <div class="container-xs xs-three">
      <div class="column">
        <hr class="latest-news-line">
      </div>
      <div class="column">
        <h5 class="latest-news-text bt-text">VIEW ALL ARTICLES</h5>
      </div>
      <div class="column">
        <hr class="latest-news-line"> 
      </div>
    </div>
  </div>
  <!-- /Latest news  -->

</template>

<style lang="scss" scoped>

/* Reviews */

.container-xs{
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 1.25rem 0;
}

.main-bt-title{
  color: white;
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
  border-radius: 50%;
  aspect-ratio: 1;
  padding: .9375rem .9375rem;
  margin-bottom: 1.5625rem;
}

.review-text{
  color: rgba(255, 255, 255, 0.9);
  font-style: italic;
  text-align: center;
  margin-bottom: 1.5625rem;
}

.review-user{
  color: white;
}

.carousel-index{
  display: flex;
  color: white;
}

.car-dot{
  width: .625rem;
  height: .625rem;
  border-radius: 50%;
  border: 0.5px solid white;
  margin: 2.5rem .25rem;
}

.active{
  background-color: white;
}

.bg-variant{
  padding: 8.5625rem 0;
  position: relative;
  overflow: hidden;
  background-image: url("../../assets/img/home-parallax-144609983.jpg");
  background-repeat: no-repeat;
  background-position: left;
  background-size: cover;
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
  background-color: #f5f5f5; 
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
  background-color: #f5f5f5;
}

.container-sm{
  display: flex;
  padding: 6.25rem 0;
}

/* /Reviews */

/* Latest news */

.main-title{
  color: var(--titles-color);
}

.cont-two{
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: #f5f5f5;
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

.img-col{
  border: .0625rem solid lightgray;
}

.hover-panel{
  display: none;
  position: absolute;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  top: 0;
  width: 15.625rem;
  height: 9.375rem;
  background-color: var(--first-color);
  color: white;
}

.hover-panel-icons{
  color: var(--first-color);
  background-color: white;
  padding: .75rem .75rem;
  margin: 0 .3125rem;
  border-radius: 50%;
}

.hover-panel-title{
  margin: .625rem 0;
}

.news-col{
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  max-width: 15.5625rem;
  padding: .3125rem .3125rem;
  color: var(--titles-color);
}

.latest-news-title{
  text-align: left;
}

.latest-news-img{
  max-width: 15.75rem;
  max-height: 9.375rem;
}

.news-date{
  margin: .3125rem 0;
}

.news-hr{
  width: 100%;
  background-color: lightgray;
}

.news-text{
  font-size: .9375rem;
}

.latest-news-hr{
  width: 8%;
}

.desc-text{
  color: var(--titles-color);
  text-align: center;
  margin: .9375rem 0;
}

.row-two{
  display: flex;
  justify-content: space-between;
}

.column{
  position: relative;
  width: calc(96% / 3);
  margin: 0 .625rem;
  text-align: center;
}

.column:hover{
  
  .hover-panel{
    display: flex;
  }

}

.latest-news-text{
  color: var(--titles-color);
  text-align: left;
  padding: .9375rem .3125rem;
}

.bt-text{
  text-align: center;
}

.latest-news-line{
  width: 100%;
  background-color: lightgray;
}

/* /Latest news */

// Carousel slider animation



</style>