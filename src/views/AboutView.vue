<template>
  <div class="about">
    <h1>Acerca de nosotros</h1>
    <button class="button-index" @click="volverInicio">Volver al inicio</button>
  </div>
</template>

<style>
h1 {
  text-align: center;
}
</style>

<script>
export default {
  name: "About",

  methods: {
    volverInicio() {
      this.$router.push("/");
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
