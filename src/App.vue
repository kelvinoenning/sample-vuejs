<template>
  <div>
    <my-nav></my-nav>
    <div id="app">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
export default {
  name: 'app',
  components: {
    "my-nav": Navbar
  }
}
</script>

<style>
html, body{
  margin: 0px;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
