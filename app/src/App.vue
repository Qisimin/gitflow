<template>
  <div id="app">
    这里是我的git测试
    <login></login>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import login from './components/login.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    login
  }
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
