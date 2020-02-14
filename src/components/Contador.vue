<template>
  <div class="segundos">
      <div class="card-columns">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">{{ contador }}</h5>
            <button class="btn btn-primary" @click="incriment">Botão de Adicionar</button>
            
          </div>
        </div>
      </div>
    <!-- <p>{{ contador}}</p>
    <button @click="incriment">Botão de Adicionar</button> -->
  </div>
</template>

<script>
export default {
  name: "Contador",
  props: {
    msg: String
  },
  data: function() {
    return {
      contador: 0
    };
  },
  methods: {
    incriment(){
        return this.contador++;
    }
  }
};
</script>


