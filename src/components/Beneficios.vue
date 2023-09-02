<template>
    <div class="container">
        Beneficios
    </div>
</template>


<script >
export default {
    props: {
        name: String,
    },
    name: "Beneficios",
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