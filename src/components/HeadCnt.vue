<script setup>
import Header from "@/components/Header.vue";
import HrS from "@/components/HrS.vue";
import LandingMainSection from "@/components/LandingMainSection.vue";
</script>

<style scoped>
.ctn,
.header{
    width:100%;
    height:100%;
}
.main-ctn{
    height:80vh;
}
</style>

<template>
    <div class="ctn">
        <Header class="header"></Header>
        <HrS></HrS>
        <div class="main-ctn">
            <LandingMainSection></LandingMainSection>
        </div>
    </div>
</template>