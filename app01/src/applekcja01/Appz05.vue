<template>
<div id="main">
    <template v-for="auto of auta">
        <div>
            <h3 :style="{background:auto.hex_color}">kolor auta</h3>
            <h3 v-if="auto.damaged" style="background-color: red;">USZKODZONY</h3>
            <h3 v-else style="background-color: green;">SPRAWNY</h3>
            <img :src="auto.image">
            <h2>id: {{auto.id }}</h2>
            <h2>name: {{ auto.car_name }}</h2>
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
* {
    box-sizing: border-box;
    padding: 0px;
}
#main {
    width: fit-content;
    height: fit-content;
    display: flex;
}

#main>* {
    padding: 20px;
}

</style>