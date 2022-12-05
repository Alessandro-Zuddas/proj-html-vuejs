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
  
  <div class="container">
    <h1>Titolo Hero Top</h1>
    <h4 class="hero-top-desc">Descrizione Hero Top</h4>
    <button class="hero-top-btn btn-one">Button One</button>
    <button class="hero-top-btn">Button two</button>
  </div>

  <div class="container bg-variant">
    <h2>Hero Final Text</h2>
    <button class="hero-top-btn btn-three">Button three</button>
  </div>

</template>

<style scoped>

.container{
  text-align: center;
  padding: 3.125rem 0;
  /* DEBUG */
  background-color: bisque;
}

.bg-variant{
  position: relative;
  background-color: yellow;
}

.hero-top-desc{
  margin: .9375rem 0;
}

.hero-top-btn{
  padding: .3125rem .9375rem;
}

.btn-one{
  margin-right: .625rem;
}

.btn-three{
  position: absolute;
  bottom: -10%;
  left: 47.5%;
}

</style>