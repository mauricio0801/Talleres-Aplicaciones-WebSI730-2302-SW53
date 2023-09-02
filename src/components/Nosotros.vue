<template>
  <div class="container">
    Nosotros{{name}}
  </div>

</template>


<script >
export default {
  props:{
    name:String,
  },
  name:"Nosotros",
}
</script>


<style scoped>

.container{
  margin: 2px;
  background-color: black;
  font-size: 50px;
  color: #f2f2f2;
  padding: 6px;
  text-align: center;
}
</style>