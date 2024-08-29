<style scoped>
.ctn{
    margin:0 0 0 1vw;
    display:flex;
    justify-content: center;
    place-items:center;
}
h1{
    text-transform:uppercase;
    font-size:60px;
}
h1 .h-one, h1 .h-two, h1 .h-three{
    background-color:hsl(0, 0%, 80%);
    color:black;
    padding:0 1vw;
    border: 2px inset #4140402d;
}
h1 .h-one{
    font-size:30px;
}
h1 .h-two {
    background-color: rgb(0, 0, 0);
    color: rgb(255, 255, 255);
    font-style:italic;
    font-size:6vw;
    letter-spacing:20px;
    box-shadow: -3px -1px 2px 4px #25252541;
    border-radius:40px 0  40px 0;
    border: 2px inset #25252502;
}
h1 .h-three {
    font-size: 40px;
}
</style>

<template>
    <div class="ctn">
        <h1>
            <small class="h-one">
                Let's 
                <b class="drive">
                    drive
                </b>
            </small>
            <br>
            <b class="h-two">
                beyond
            </b>
            <br>
            <b class="h-three">
                earth
            </b>
        </h1>
    </div>
</template>