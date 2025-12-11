<script setup>
import profile from "./../components/profile.vue"
import newButon from "./../components/button.vue"
import menuButtons from "./../components/menu.vue"
</script>

<template>
    <div id="profileHeader">
        <profile />
        <newButon />
    </div> 
        <menuButtons />
        <hr>
</template>

<style scoped>
#profileHeader {
    display: grid;
    grid-template-columns: 17% 50% 33%;
    background-color: rgba(250, 235, 215, 0.666);
    padding: 0px 0px 10px 0;
}
hr {
    margin: auto;
}
</style>