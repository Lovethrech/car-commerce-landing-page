<script setup>
import Header from "@/components/Header.vue";
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
.img-ctn{
    position:;
    width:100%;
    height:100%;
    background: url("/erik.jpg") top/100% auto no-repeat;
}
.img-overlay{
    position:absolute;
    top:0;
    width:100%;
    min-height:40vh;
    height: 80vh;
    z-index:2;
    background-color: rgba(0, 0, 0, 0.253);
}
</style>


<template>
    <div class="ctn">
        <div class="main-ctn">
            <div class="header">
                <!-- <Header></Header> -->
            </div>
            <div class="bg-slide">
                <div class="img-ctn">
                    <div class="img-overlay"></div>
                </div>
                <!-- <div class="img-overlay"></div> -->
            </div>
            <!-- <HeadCtnText></HeadCtnText> -->
        </div>
    </div>
</template>