<script setup>
    import { ref } from 'vue'

    // Add code here
    const selected = ref('Username login')

</script>

<template>
    <h1>Please select your login option</h1>
    <!-- Add/modify code in the following to have a dropdown list 
        which lets the user to select either to login with username or email -->
    <select v-model="selected">
        <option selected value="username">Username login</option>
        <option value="email">Email login</option>
    </select>
    
    <div v-if="selected === 'username'">
        <label>Username
        <input placeholder="Enter your username">
    </label>
    </div>

    <div v-else>
        <label>Email
        <input placeholder="Enter your email address">
        </label>
    </div>
</template>
