<template>
  <h1>Welcome {{ name }}</h1>
</template>

<script>

export default {
  name: 'App',
  data: function() {
    return {
      name: "Anurag"
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
