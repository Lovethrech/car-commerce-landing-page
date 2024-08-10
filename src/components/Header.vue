<script setup>
import Nav from "@/components/Nav.vue";
</script>

<style scoped>
.ctn{
    background:hsla(0, 0%, 0%, 0.623);
    position:relative;
    padding: 1vh 5vw;
}
.main-ctn{
    display:flex;
    flex-direction:row;
    justify-content: space-between;
}
.logo-ctn{
    width:4vw;
    height:4vh;
}

.logo-ctn img{
    width:100%;
    height:100%;
}
.nav-ctn{
    display:flex;
    justify-content: center;
    place-items: center;
}
</style>

<template>
    <div class="ctn">
        <div class="main-ctn">
            <div class="logo-ctn">
                <img src="/Chel logo.svg" alt="">
            </div>
            <div class="nav-ctn">
                <Nav></Nav>
            </div>
        </div>
        
    </div>
</template>