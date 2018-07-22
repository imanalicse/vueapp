<template>
  <div id="app">
    <!-- <test msg="Hello message"/> -->
    <users/>
  </div>
</template>

<script>
 import test from './components/test'
 import users from './components/users'

export default {
  name: 'App',
  components: {
    test,
    users
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
