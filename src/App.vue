<template>
  <img class="PokeLogo" alt="PokeLogo" src='./assets/poke.png'>
  <PokeApi/>
</template>

<script>
import PokeApi from './components/PokeApi.vue'

export default {
  name: "App",
  components: {
    PokeApi
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.PokeLogo {
  width: 500px;
  display: block;
  position: relative;
  margin-left: 500px;
  margin-bottom: 40px;
}

</style>