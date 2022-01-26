<template>
  <div class="header">
    <img src="../assets/logo.png" alt="">
  </div>
</template>

<script>
export default {
  name: 'Title',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header{
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: start;
}
.header>img{
  width: 80px;
  margin: 0 15px;
}
</style>
