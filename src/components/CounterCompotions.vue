<template>
    <h1>Componente con estilo Compositions API </h1>
    <h2>{{ counter }}</h2>
    <button @click="addCounter">Incrementar</button>
</template>
<script>
import { defineComponent,ref } from "vue";
export default defineComponent({
    name:'CounterCompotions',
    setup(){
        let counter= ref(0);
        const addCounter = ()=>{
            counter.value++
        }
        return { counter,addCounter}
    }
})
</script>