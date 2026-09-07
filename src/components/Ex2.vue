<script setup>
    import { ref } from 'vue'

    // Add code here
    const me = ref('/assets/me.png')
    const width = ref('200')
    const height = ref('200')
    // const img2 = { src: me.value, width: width.value, height: height.value }

    const obj = {
        width: '200',
        height: '200',
        src: '/assets/me.png'
    }

</script>

<template>

    <!-- Add code here -->
    <!-- single attribute binding: each attribute bound separately -->
    <img v-bind:src="me" :width="width" :height="height">
    
    <!-- multiple attribute binding: one object holds all the attributes at once -->
    <img v-bind="obj">
</template>
