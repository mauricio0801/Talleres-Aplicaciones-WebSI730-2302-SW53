<template>
  <div class="container">
    Contactanos

    <button @click="handleClick" > Clickea aqui</button>
  </div>
</template>


<script >
export default {
  props: {
    name: String,
  },
  name: "Contactanos",
  methods: {
    handleClick(){
      alert('992928323')
    }
  }

}
</script>


<style scoped>
.container {
  margin: 2px;
  background-color: black;
  font-size: 50px;
  color: #f2f2f2;
  padding: 6px;
  text-align: center;
  border-radius: 30px;
  font-family: sans-serif;

}
.container:hover{
  background-color: red;

}
</style>