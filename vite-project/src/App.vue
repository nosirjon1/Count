<script setup>
// import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
import {ref} from "vue"
const count = ref(0)
</script>

<template>

  <div class="a">
    <h3>The current count is...</h3>
    <h1>{{ count }}</h1>
    <button @click="count--">-</button>
    <button @click="count++">+</button>
  </div>
</template>

<style scoped>
.a{
  height: 300px;
  width: 350px;
  margin: 0 auto;
  background-color: aquamarine;
  
  justify-content: center;
  align-items: center;
 }
</style>
