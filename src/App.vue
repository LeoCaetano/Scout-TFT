<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    
    <div class="container">
      <div class="row">
        <div class="col-3">
          <jogador/>
        </div>
        <div class="col-3">
          <jogador/>
        </div>
        <div class="col-3">
          <jogador/>
        </div>
        <div class="col-3">
          <jogador/>
        </div>
      </div>
    </div>

    <div class="container">
      <div class="row">
        <div class="col-4">
          <jogador/>
        </div>
        <div class="col-4">
          <jogador/>
        </div>
        <div class="col-4">
          <jogador/>
        </div>
      </div>
    </div>
    
  </div>
</template>

<script>
import Jogador from './components/Jogador.vue'

export default {
  name: 'App',
  components: {
    Jogador
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
</style>
