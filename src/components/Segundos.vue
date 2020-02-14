<template>
  <div class="segundos">
      <div class="card-columns">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title">Este site esta abrerto a {{ segundos }} segundos</h5>
            
          </div>
        </div>
      </div>
    <!-- <p>Este site esta abrerto a {{ segundos }} segundos</p> -->
  </div>
</template>

<script>
export default {
  name: "Segundos",
  props: {
    msg: String
  },
  data() {
    return {
      segundos: 0
    };
  },
  created() {
      setInterval(() => {
        this.segundos++;
      }, 1000);
    }
}
</script>




