<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.jpg" height="150px" width="150px" style="border-radius: 75px;">
    <p>
      <router-link to="/">Home</router-link> &nbsp;&nbsp;
      <router-link to="/about">About</router-link>
    </p>
    <h1>Mahesh Shahi</h1>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app',
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
