<script setup>
import navLists from "@/data/nav-lists.json";
</script>

<style scoped>
ul{
    display:flex;
    flex-direction: row;
    justify-content: space-between;
    gap:2vw;
}
.list{
    margin: auto 0;
    text-transform: capitalize;
}
.link-list{
    color: rgb(255, 254, 254);
    font-size:14px;
}
.link-list:hover{
    cursor:pointer;
    color:hsl(0, 0%, 0%);
}
.list:last-child{
    background-color: white;
    padding: 10px 20px;
    border-radius: 30px;
}
.list:last-child .link-list:hover{
    background: transparent;

}
.list:last-child .link-list{
    color:black;
}
</style>

<template>
    <ul>
        <div class="list" v-for="navList in navLists" :key="navList.id">
            <RouterLink to="/" class="link">
                <li class="link-list">{{ navList.name }}</li>
            </RouterLink>
        </div>
    </ul>
</template>