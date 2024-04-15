<template>
    <select>
        <option v-for="color of prop1" :value="color" @click="zmiana(color)" :style="{background:color}">{{color}}</option>
    </select>
    </template>
    
    <script>
        export default {
            props: ["prop1"],
            methods:{
                zmiana(digit){
                    alert(digit)
                }
            }
        }
    </script>
    
    <style scoped>
    
    </style>