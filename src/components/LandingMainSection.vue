<script setup>
import LMSText from "@/components/LMSText.vue";
</script>

<style scoped>
.ctn, .main-ctn{
    width:100%;
    height:100%;
}
.ctn{
    display:flex;
    justify-content: center;
    place-items:center;
    background: transparent;
    color:white;
}
.main-ctn{
    display:flex;
    background: url("/pex.jpg") right/600px no-repeat;
}
</style>

<template>
    <div class="ctn">
        <div class="main-ctn">
            <LMSText></LMSText>
        </div>
    </div>
</template>