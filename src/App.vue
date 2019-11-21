<template>
  <div id="app">
    <h3>{{ titulo }}</h3>
    <div class="form">
      <div class="form-group">
        <label>Título</label>
        <input type="text" class="form-control" v-model="nota.titulo">
      </div>
      <div class="form-group">
        <label>Texto</label>
        <textarea class="form-control" v-model="nota.texto"></textarea>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      titulo: 'Gestión de notas',
      nota: {
        titulo:'',
        texto:''
      }
    };
  }
};
</script>

<style>
  #app {
    font-family: Arial, Helvetica, sans-serif;
    text-align: center;
    color: #2C3E50;
    margin: 20px;
  }

  .form{
    text-align: left;
  }
</style>
