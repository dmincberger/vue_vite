<template>
<div id="main">
    <template v-for="auto of auta">
        <div>
            <h3 :style="{background:auto.hex_color}">kolor auta</h3>
            <h3 v-if="auto.damaged" style="background-color: red;">USZKODZONY</h3>
            <h3 v-else style="background-color: green;">SPRAWNY</h3>
        </div>
    </template>
</div>
</template>

<script>
import Cars from "./data/cars.json"
export default {
    data(){
        return{
            auta:Cars
        }
    },
}
</script>

<style>
</style>