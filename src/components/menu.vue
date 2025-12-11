<script setup>

</script>

<template>
    <div id="menuButtons">
        <button class="nopicked">19.08</button>
        <button class="picked">Today</button>
        <button class="nopicked">21.08</button>
        <button class="nopicked">Tomorrow</button>
    </div>
</template>

<style>
#menuButtons {
    background-color: rgba(250, 235, 215, 0.666);
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 25px;
    padding: 0px 15px 10px 15px;
    
}

.picked {
    font-family: Arial, Helvetica, sans-serif;
    background-color: rgb(29, 149, 255);
    box-shadow: 2px 2px rgba(250, 235, 215, 0.666);
    border-radius: 10px;
    height: 60%;
    margin: 10px 0px 0px 0px;
    color: white;
    padding: 5px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.nopicked {
    font-family: Arial, Helvetica, sans-serif;
    background-color: white;
    box-shadow: 2px 2px  black;
    border-radius: 10px;
    height: 60%;
    margin: 10px 0px 0px 0px;
    color: black;
    padding: 5px;
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>