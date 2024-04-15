<template>
<div id="main">
    <ColorSelect :prop1="color_array"></ColorSelect>
</div>
</template>

<script>
export default {
    data(){
        return {
            color_array: ["red","black","blue","brown","green"]
        }
    },
    components: { ColorSelect }
}
import ColorSelect from "../lekcja1/ColorSelect.vue"
</script>

<style>

</style>