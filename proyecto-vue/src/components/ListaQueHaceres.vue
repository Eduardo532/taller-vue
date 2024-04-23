<script setup>
import{ref} from 'vue'
const nombre = ref('')

var ListaQH = new Vue({
    el: '#ListaQH',
    data:{
        items:[
            name=null
        ]
    }
})
</script>

<template>
    <div class="">
        <h3>nombre : <input v-model.lazy="nombre"/> </h3>
        <h3>Que hacer</h3>



        <h2>Nombre: {{ nombre }}</h2>
        <h2 id="ListaQH">Que haceres: 
            <li v-for="item in items"></li>
        </h2>
        
    </div>
</template>


<script>
export default {
    name: 'ListaQueHaceres'

    
}
</script>


<style scoped>


</style>