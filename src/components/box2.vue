<script setup>

</script>

<template>
    <div id="box2">
        <h3>Meditation</h3>
        <input type="radio">
        <p>11:30 PM - 13:00 PM - Health</p>
    </div>
</template>

<style scoped>
#box2 {
    display: grid;
    grid-template-columns: 80% 20%;
    background-color: rgb(0, 146, 71);
    border: 1px solid black;
    border-radius: 10px;
    color: white;
    box-shadow: 9px 8px black;
    margin: 20px 15px 0px 10px;
}
h3 {
    font-family: Arial, Helvetica, sans-serif;
    margin: 12px 18px 10px 18px;
}
p {
    font-family: Arial, Helvetica, sans-serif;
    font-size: small;
    margin: 0px 18px 10px 18px;

}
input {
    height: 110%;
    width: 30%;
    margin: 10px 0px 0px 30px;
}
</style>