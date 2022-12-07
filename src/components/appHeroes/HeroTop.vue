<script>
export default {

    name: "HeroTop",

    data() {
        return {
        
        }
    }
}
</script>

<template>
  
  <div class="container cont-one">
    <div class="img-container">
      <h1 class="hero-top-title">BUILDING INSPIRING SPACES</h1>
      <h4 class="hero-top-desc">We Build Inspiring Residential & Commercial Spaces</h4>
      <button class="hero-top-btn btn-one">EXPLORE RECENT WORK</button>
      <button class="hero-top-btn btn-two">GET A QUOTE TODAY</button>
    </div>
  </div>

  <div class="container bg-variant">
    <h2 class="hero-top-title-two">Do You Have A Construction Project We Can Help With?</h2>
    <button class="hero-top-btn btn-three">GET A FREE QUOTE</button>
  </div>

</template>

<style scoped>

.container{
  text-align: center;
  background-image: url("../../assets/img/home-slider-62528242.jpg");
}

.cont-one{
  padding: 15.625rem 0;
}

.hero-top-title{
  font-size: 3.125rem;
  color: white;
}

.bg-variant{
  position: relative;
  background-color: var(--first-color);
  padding: 3.125rem 0;
  background-image: none;
}

.hero-top-title-two{
  font-size: 1.25rem;
}

.hero-top-desc{
  color: var(--first-color);
  font-size: 1.25rem;
  margin: .9375rem 0;
}

.hero-top-btn{
  border: none;
  padding: .625rem .9375rem;
  cursor: pointer;
}

.btn-one{
  color: white;
  background-color: var(--second-color);
  margin-right: .625rem;
}

.btn-one:hover{
  color: var(--titles-color);
  background-color: var(--first-color);
}

.btn-two{
  background-color: var(--first-color);
  color: gray;
}

.btn-two:hover{
  background-color: var(--second-color);
  color: white;
}

.btn-three{
  position: absolute;
  bottom: -15%;
  left: 45.8%;
  color: white;
  background-color: var(--second-color);
  border: 1px solid white;
}

.btn-three:hover{
  background-color: white;
  color: black;
  border: .0625rem solid black;
}

</style>