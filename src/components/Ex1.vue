<script setup>
    import { ref } from 'vue'

    // Add code here
    // challenge: use array  

    const message = ref('Choose your favorite fruit: ')
    const fruit1 = ref('apple')
    const fruit2 = ref('orange')
    const fruit3 = ref('peach')

    //const fruits = ref(["apple","orange","peach"])

</script>

<template>
    {{ message }} 
   
    <label for=""> <input type="radio" name="fruit"> {{ fruit1 }} </label> 
    <label for=""> <input type="radio" name="fruit"> {{ fruit2 }} </label> 
    <label for=""><input type="radio" name="fruit"> {{ fruit3 }} </label> 

    <!-- <label for=""> <input type="radio" name="fruit"> {{ fruit[0] }} </label> 
    <label for=""> <input type="radio" name="fruit"> {{ fruit[1] }} </label> 
    <label for=""><input type="radio" name="fruit"> {{ fruit[2] }} </label> using array -->

    <!-- <label v-for="fruits in fruits" :key="fruit">
        <input type="radio" name="fruit">{{ fruit }}
    </label> for loop using vue -->
    
</template>

<style scoped>
</style>
