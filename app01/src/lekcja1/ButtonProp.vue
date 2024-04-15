<template>
<h3>{{this.prop1}}</h3>
<div :style="{ background: prop2 }">
    hmmm
</div>
</template>

<script>
export default {
    props: ["prop1", "prop2"]
}

</script>

<style>

</style>