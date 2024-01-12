<template>
  <div class="box">
    <span>Name: Chan Narong</span>
    <span>Grade: 7</span>
    <span>Age: 18</span>
    <h1>narong  bek sloy</h1>
  </div>


</template>
<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.box {
  border: 1px solid #000;
  padding: 10px;
  margin: 10px;
}
span {
  display: block;
  margin-bottom: 10px;
} 
</style>
