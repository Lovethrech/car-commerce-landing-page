<script setup>
import LMSText from "@/components/LMSText.vue";
import LMSImg from "@/components/LMSImg.vue";
</script>

<style scoped>
.ctn{
    display:flex;
    justify-content: center;
    place-items:center;
    width:100%;
    height:100%;
    background: transparent;
    color:white;
}
.main-ctn{
    display:flex;
    
}
</style>

<template>
    <div class="ctn">
        <div class="main-ctn">
            <LMSText></LMSText>
            <LMSImg></LMSImg>
        </div>
    </div>
</template>