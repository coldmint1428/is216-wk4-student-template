<script setup>
    import { ref } from 'vue'

    // Add code here
    const me = ref('/assets/me.png')
    const width = ref(300)
    const height = ref(200)

    const imgProps = { src: me.value, width: width.value, height: height.value }

</script>

<template>

    <!-- Add code here -->
     <img v-bind:src="me" v-bind:width="width" v-bind:height="height">

    
    <img v-bind="imgProps">
    
</template>
