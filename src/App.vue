<template>
  <div id="app">
    <Title></Title>
    <Jumbotron></Jumbotron> 
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Jumbotron from './components/Jumbotron.vue'

export default {
  name: 'App',
  components: {
    Title,
    Jumbotron
  },
  
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}
</style>
