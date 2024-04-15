<template>
<select>
    <option v-for="digit of array" :value="digit" @click="zmiana(digit)">{{digit}}</option>
</select>
</template>

<script>
    export default {
        data(){
            return {
                array: [1,2,3]
            }
        },
        methods:{
            zmiana(digit){
                alert(digit)
            }
        }
    }
</script>

<style scoped>

</style>