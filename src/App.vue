<template>
  <HeaderPage/>
</template>

<script>
import HeaderPage from './components/HeaderPage.vue'
export default {
  name: 'App',
  components: {
    HeaderPage
}
}
</script>

<style lang="scss">
@import './assets/variables.scss';
@import './assets/fonts.scss';

body{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Poppins'
}

</style>
