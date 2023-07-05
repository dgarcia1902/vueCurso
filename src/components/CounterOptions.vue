<template>
// Contador con Otion Api
<h1>Componente con estilo Option API </h1>
<h3>{{ counter }}</h3>
<button @click="addCounter">Incremetar</button>
</template>
<script>
import { defineComponent } from "vue";
export default defineComponent({
    name:'CounterOptions',
    // components:{se define que components vamos a importar }
    data(){
        let counter =0
        return {counter}
    },
    methods:{
        addCounter(){
            this.counter++
        }
    }
})
</script>

<style>
</style>