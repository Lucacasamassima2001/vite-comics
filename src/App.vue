<script>

import AppHeader from './components/AppHeader.vue';
import AppProducts from './components/AppProducts.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  
  components: {
    AppHeader,
    AppProducts,
    AppFooter,
  }

}
</script>


<template>
  <appHeader></appHeader>

  <main>
  <app-products></app-products>
  </main>
  
  <app-footer></app-footer>
</template>


<style lang="scss">

*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

</style>