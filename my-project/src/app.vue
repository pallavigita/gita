<template>
  <div id="app">
    <img src="./assets/logo.png">
    <skills/>
</template>

<script>
import skills from'./components/skills.vue '

export default{ 
  name: 'App',
  components: {
    skills
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
