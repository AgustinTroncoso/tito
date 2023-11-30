<script setup>

import Componente1 from '../components/componente1.vue'
import Componentes2 from '../components/Componentes2.vue'
import Componente3 from '../components/componente3.vue'
</script>

<template>
    <div class="navbar">
    <Componente3>

    </Componente3>
</div>
<div class="cartcontainer">
    <Componente1></Componente1>
</div>
<div class="botonContainer">
<Componentes2/>
</div>
</template>

<style>
.navbar{

}
.cartcontainer{
    float:middle
}
.botonContainer{
vertical-align: bottom;
}

</style>
