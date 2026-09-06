<script setup>
    import { ref, reactive } from 'vue'

    // Add code here
    const me = ref('/public/assets/me.png')
    const width = ref(300)
    const height = ref(200)

    const imgProps = reactive({ src: me, width: width, height: height })

</script>

<template>

    <!-- Add code here -->
    <!-- single attribute binding: each attribute bound separately -->
    <img v-bind:src="me" v-bind:width="width" v-bind:height="height">

    <!-- multiple attribute binding: one object holds all the attributes at once -->
    <img v-bind="imgProps">
</template>
