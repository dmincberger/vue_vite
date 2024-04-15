<template>
    <div id="main">
        {{ message }}
    </div>
    <MyButton></MyButton>
</template>
  
<script>
export default {
    data() {
        return {
            message: 'Hello World',
        };
    },
    components: { MyButton }
};

import MyButton from "./lekcja1/Buttonz01.vue"

</script>
  
<style>
#main {
    font-size: 18px;
    font-family: 'Roboto', sans-serif;
    color: blue;
}
</style>


