<template>
<div id="main">
<h1>{{ message }}</h1>
</div>

<ButtonProp :prop1="buttontitle" :prop2="Kolor"></ButtonProp>

</template>

<script>
import ButtonProp from "./lekcja1/ButtonProp.vue"
export default{
    data(){
        return{
            message: "HEJ",
            buttontitle: "ButtonTitle",
            Kolor: "red"
        }
    }, 
    components: { ButtonProp}
}
</script>

<style>
#main{
    width: 200px;
    height: 200px;
    align-items: center;
    justify-content: center;

}
</style>