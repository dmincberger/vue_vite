<template>
<button @click="Tekst()">{{ tekst }}</button>
</template>

<script>
export default {
    data(){
        return{
        tekst: "Dowolny tekst"
        }
    },
    methods: {
        Tekst(){
            alert("BOO")
        }
    }
}
</script>

<style scoped>
button {
    width: 300px;
    height: 300px;
    justify-content: center;
    align-items: center;
    /* background-color: violet; */
}
</style>