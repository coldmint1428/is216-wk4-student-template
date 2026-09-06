<script setup>
    import { ref } from 'vue'

    // Add code here
    const me = ref('/assets/me.png')
    const width = ref(300)
    const height = ref(200)

</script>

<template>

    <!-- Add code here -->
    <!-- single attribute binding: each attribute bound separately -->
    <img v-bind:src="me" v-bind:width="width" v-bind:height="height">

    <!-- multiple attribute binding: one object holds all the attributes at once -->
    <img v-bind="{ src: me, width: width, height: height }">
</template>
