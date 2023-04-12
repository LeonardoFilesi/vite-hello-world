<script>
export default {
    name: "AppHero",
    data() {
        return {
            jumbo: "Questo è un Jumbotron, daje!!!"
        }
    }
}
</script>

<template>
    <div class="jumbo-background">
        <h2>{{ jumbo }}</h2>
        <img src="../assets/vue.svg" alt="">
    </div>
</template>

<style>
.jumbo-background {
    background-color:  rgb(44, 82, 59);
    text-align: center;
}
h2 {
    background-color:  rgb(44, 82, 59);
}
img {
    background-color: rgb(44, 82, 59);
}
</style>