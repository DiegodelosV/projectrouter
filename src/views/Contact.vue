<template>
  <h1>Información de contacto</h1>
  <br />
  <div>
    <button class="button-index" @click="volverInicio">Volver al inicio</button>
  </div>
</template>

<script>
export default {
  name: "Contact",
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
