<script>
import AppHeader from './components/appHeader/AppHeader.vue';
import HeroTop from './components/appHeroes/HeroTop.vue';
import AppMain from './components/appMain/AppMain.vue';
import HeroBottom from './components/appHeroes/HeroBottom.vue';
import AppFooter from "./components/appFooter/AppFooter.vue"

export default {
  components: {
    AppHeader,
    HeroTop,
    AppMain,
    HeroBottom,
    AppFooter
  }
}
</script>

<template>
  <div>
    <AppHeader/>
    <HeroTop/>
    <AppMain/>
    <HeroBottom/>
    <AppFooter/>
  </div>
</template>

<style lang="scss" scoped>

@import "./style/global.scss";

</style>
