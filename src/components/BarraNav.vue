<script setup>
import Beneficios from './Beneficios.vue';
import Inicio from './Inicio.vue';
import Nosotros from './Nosotros.vue';
import AcercaDe from './AcercaDe.vue';

</script>
<template>
    <div  class="container2" >
        <Inicio/>
        <Nosotros />
        <Beneficios/>
        <AcercaDe/>
    </div>
</template>

<script>
export default {
    name: "BarraNav",
    components: { Inicio, Nosotros },
}
</script>

<style scoped>
.container2 {
    width:100%;
    display: flex;
    flex-direction: row;
    position: absolute;
    top: 0;
    left: 0;
    height: 100px;
    background-color: aqua;
    
}

</style>