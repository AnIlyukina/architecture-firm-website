<template>
  <HeaderPage/>
  <AboutFirm/>
  <OurTeam/>
</template>

<script>
import HeaderPage from './components/HeaderPage.vue'
import AboutFirm from './components/AboutFirm.vue'
import OurTeam from './components/OurTeam.vue'
export default {
  name: 'App',
  components: {
    HeaderPage, 
    AboutFirm,
    OurTeam
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
