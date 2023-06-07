<template>  
  <NavBar/>
  <HeroMain/>
</template>

<script>
import NavBar from './components/NavBar.vue'
import HeroMain from './components/HeroMain.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    HeroMain
  }
}
</script>

<style>
@import './css/style.css';
</style>
