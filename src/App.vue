<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'

let meineFunktion = function name(msg:String) {

  return msg;
}

let var1 = meineFunktion('Das ist ein Test');


</script>

<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld class="button" msg="Hello Vue 3 + TypeScript + Vite" />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #83b0dd;
  margin-top: 60px;
}
</style>
