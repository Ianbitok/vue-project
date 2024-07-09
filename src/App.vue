<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
  <v-toolbar color="green">
    <v-tab to="/">Home</v-tab>
    <v-tab to="/about">About</v-tab>
    <v-tab to="/contact">Contact</v-tab>
    <v-tab to="/login">Login</v-tab>
    <v-tab to="/signup">Sign Up</v-tab>
  </v-toolbar>
        <RouterView/>
</template>