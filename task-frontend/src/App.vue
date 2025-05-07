<template>
  <div>
    <index/>
  </div>
</template>

<script setup lang="ts">
import { defineProps } from 'vue'
import { useRoute } from 'vue-router'
import { useStore } from 'vuex' 
import index from './pages/index.vue'
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif; 
  color: #2c3e50; 
}
</style>