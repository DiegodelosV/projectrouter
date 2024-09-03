<template>
  <h1>Información de los Productos</h1>
  <p>Estos son los Productos</p>
  <ul>
    <li>Producto 1</li>
    <li>Producto 2</li>
    <li>Producto 3</li>
  </ul>
  <div>
    <router-link to="/">Volver</router-link>
    <br />
    <button class="button-index" @click="volverInicio">Volver al inicio</button>
  </div>
</template>

<script>
export default {
  name: "Products",
  methods: {
    volverInicio() {
      return;
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
