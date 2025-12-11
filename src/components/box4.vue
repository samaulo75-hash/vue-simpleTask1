<script setup>

</script>

<template>
    <div id="boxRed">
        <h3>UserFlow app</h3>
        <input type="radio">
        <p>15:00 PM - 15:30 PM - Health</p>
    </div>
</template>

<style scoped>
    #boxRed {
    display: grid;
    grid-template-columns: 80% 20%;
    background-color: rgb(244, 99, 99);
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