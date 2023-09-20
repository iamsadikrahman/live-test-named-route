<template>
    <div>
      <h1>Home Component</h1>
      <router-link :to="{ name: 'user-profile', params: { username: 'johndoe' } }">Go to John Doe's Profile</router-link>
    </div>
  </template>
  
  <script setup>
  import { defineProps, defineEmits } from 'vue';
  
  const props = defineProps();
  const emits = defineEmits();
  </script>
  