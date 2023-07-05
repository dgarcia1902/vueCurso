<template>
    <div class="post-Container">
        <PostCard/>
        <PostCard/>
        <PostCard/>
        <PostCard/>
    </div>
</template>
<script setup>
import PostCard from "./PostCard.vue";
</script>
<style scoped>
.post-Container{
    width: 100%;
    display: flex;
    flex-wrap: wrap;
}
</style>