<script>

import MainTop from './MainTop.vue';
import MainMiddle from './MainMiddle.vue';
import MainBottom from './MainBottom.vue';

export default {

    name: "AppMain",

    components: {

      MainTop,
      MainMiddle,
      MainBottom,

    },
    data() {
      return {
      
      }
    }
}
</script>

<template>

  <MainTop/>
  <MainMiddle/>
  <MainBottom/>

</template>

<style scoped></style>