<template>
  <div id="main">
      <div class="container">
          <div class="card">
              <div class="card-body"> 
                  <h1>{{Nome}} <span class="fa fa-check"></span></h1>
                   <input type="text" v-model="Nome"> 
              </div>

          </div>

      </div>

  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css"
import "font-awesome/css/font-awesome.css"
export default {
    name: "Jogador",
    data: function(){
        return {
            Nome:"Teste"
        }

    }
}
</script>

<style>

</style>