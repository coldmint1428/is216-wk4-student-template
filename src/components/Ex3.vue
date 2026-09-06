<script setup>
    import { ref } from 'vue'

    // Add code here

    
    
</script>

<template>
    <h1>Please select your login option</h1>
    <!-- Add/modify code in the following to have a dropdown list 
        which lets the user to select either to login with username or email -->
    <select>
        <option selected>Username login</option>
        <option>Email login</option>
    </select>
    
    <div>
        <label>Username <v-if></v-if></label>
        <input placeholder="Enter your username">
    </div>

    <div>
        <label>Email</label>
        <input placeholder="Enter your Email">
    </div>
</template>

