<script setup>
import Header from "@/components/Header.vue";
import HrS from "@/components/HrS.vue";
import HeadCtnText from "@/components/HeadCtnText.vue";
</script>


<style scoped>
.ctn,
.main-ctn,
.header,
.bg-slide{
    width:100%;
    height:100%;
}
.img-ctn img{
    width:fit-content;
}
.bg-slide{
    width:100%;
    min-height:40vh;
    height: 80vh;
}

</style>


<template>
    <div class="ctn">
        <div class="main-ctn">
            <div class="header">
                <Header></Header>
            </div>
            <HrS></HrS>
            <!-- <div class="bg-slide">
                <div class="img-ctn">
                    <div class="img-overlay"></div>
                </div>
                <div class="img-overlay"></div>
            </div> -->
            <!-- <HeadCtnText></HeadCtnText> -->
        </div>
    </div>
</template>