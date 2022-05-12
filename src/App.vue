<template>
  <div id="app">
    <img alt="Emme" src="./assets/Emme pls.gif"/>
    <Title msg="La mia prima app con Vue CLI gasp!"></Title>
    <Hero msg="Già che ci siamo ecco un jumbotron va'" mgsButton="Beccati anche un buttone a random to'">
      <img src="./assets/img_jumbotron.png"/>
    </Hero>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components:{
    Title,
    Hero
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  
  img {
    width:auto;
    max-width: 60%;
  }
}
</style>
