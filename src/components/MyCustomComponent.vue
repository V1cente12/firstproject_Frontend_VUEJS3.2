<!-- src/components/MyCustomComponent.vue -->
<template>
  <div>
    <h1>Hola desde MiComponente</h1>
    <p>{{ mensaje }}</p>
  </div>
</template>

<script>
export default {
  name: 'MyCustomComponent', // Nombre cambiado a multi-palabra
  data() {
    return {
      mensaje: 'Este es un componente personalizado en Vue'
    };
  }
};
</script>

<style scoped>
h1 {
  color: blue;
}
</style>
