<template>
  <div>
    <h1>Servicios</h1>
    <button class="button-index" @click="volverInicio">Volver al inicio</button>
  </div>
</template>

<script>
export default {
    name: 'Services',
    methods: {
    volverInicio() {
      return this.$router.push("/");
    },
  },
};
</script>

<style>
.button-index {
  margin-top: 10px;
  padding: 5px;
  color: white;
  background-color: #42b983;
}
</style>
