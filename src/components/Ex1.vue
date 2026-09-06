<script setup>
    import { ref } from 'vue'

    // Add code here
    // challenge: use array  

    const message = ref('')
    const fruit1 = ref('apple')
    const fruit2 = ref('orange')
    const fruit3 = ref('peach')

</script>

<template>
    {{ message }} 
   
    <label for=""> <input type="radio" name="fruit" :value="fruit1" v-model="message"> {{ fruit1 }} </label> 
    <label for=""> <input type="radio" name="fruit" :value="fruit2" v-model="message"> {{ fruit2 }} </label> 
    <label for=""> <input type="radio" name="fruit" :value="fruit3" v-model="message"> {{ fruit3 }} </label> 
    
</template>

<style scoped>
</style>
