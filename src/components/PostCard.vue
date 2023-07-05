<template>
    <div class="post-card">
        <h3>Titulo</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Facilis velit nemo ea assumenda fugit nobis aliquid sed debitis, quam temporibus animi quae vitae magnam tempora provident, aspernatur eos! Voluptatibus, itaque.</p>
        <PostButton/>
    </div>
</template>


<script setup>
import PostButton from "./PostButton.vue";
</script>
<style scoped>
.post-card{
    border-radius: 15px;
    padding: 16px;
    margin: 5px;
    border: 1px solid #ccc;
}
</style>