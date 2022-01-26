<template>
<div class="jumbo">
  <div class="green-arrow">
      <div class="square">
        <div class="jumbo-text">
          <h3>Jumbotron</h3>
          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Perspiciatis, sapiente. Accusamus blanditiis quasi esse odit ullam expedita veritatis magnam, explicabo autem cumque ex animi. Voluptatibus tenetur doloribus corporis veniam impedit.</p>
        </div>
      </div>
      <div class="triangle"></div>
  </div>
</div>
</template>

<script>
export default {
  name: 'Jumbotron',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped >
.jumbo{
  height: 700px;
  background-color: #41b883;
}
.green-arrow{
  position: relative;
  display: flex;
}

.square{
  background-color: #35495e;
  height: 700px;
  width: 65%;
  display: flex;
  align-items: end;
}
.triangle{
  width: 0; 
  height: 0; 
  border-top: 350px solid transparent;
  border-bottom: 350px solid transparent;
  border-left: 200px solid #35495e;

}
.jumbo-text{
  color: white;
  width: 500px;
  margin-left: 30px;
  margin-bottom: 140px;
}
.jumbo-text>h3{
  font-size: 120px;
  margin-bottom: 20px;
}
.jumbo-text>p{
  font-size: 16px;
  font-style: italic;
  margin-left: 50px;
}
</style>
