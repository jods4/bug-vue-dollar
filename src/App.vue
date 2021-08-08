<template>
  <div>v$Hello = {{ v$Hello ?? 'Bug!' }}</div>  
  <div>v$Hello as vHello = {{ vHello ?? 'Bug!' }}</div>  
</template>

<script setup lang="ts">
import { v$Hello } from './module';
import { v$Hello as vHello } from './module';

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/master/active-rfcs/0040-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
