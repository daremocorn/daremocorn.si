<template>
  <div id="app">
    <profile></profile>
  </div>
</template>

<script>
import Profile from '@/components/Profile'

export default {
  name: 'app',
  components: {
    Profile
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #F8F8F2;
  margin-top: 60px;
}
</style>
