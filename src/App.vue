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
  <HelloWorld msg="Hello Vue 3 + TypeScript + Vite Erster" />
</template>

<style>

</style>
