<script setup>
    import { ref } from 'vue'

    // Add code here
    const me = ref('/public/assets/me.png')

</script>

<template>

    <!-- Add code here -->
   <img v-bind:src="me">
</template>
