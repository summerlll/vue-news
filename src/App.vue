<template>
  <div id="app">
    <h1>v1 版本的 news</h1>
    <h2>修复 v1版本的 bug</h2>
    <img src="./assets/logo.png">
    <router-view/>

    <h2>第二个版本的 news</h2>

  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
