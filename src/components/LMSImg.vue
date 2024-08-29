<script setup>
import { ref } from "vue";
</script>

<style scoped>
.ctn,
.ctn img{
    width:100%;
    border-radius:180px 0 0 180px;
}
.ctn img{
    box-shadow: -12px -10px 2px 10px #25252541;
    border:20px inset #25252502;
}
</style>

<template>
    <div class="ctn">
        <img src="/sam.jpg" alt="">
    </div>
</template>