<template>
  <div id="app">
    <h3>{{ msg }}</h3>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      msg: "Hola Mundo pendejos! :v"
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
</style>
