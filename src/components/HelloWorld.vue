<script setup lang="ts">
import { ref } from 'vue'
import { NButton } from 'naive-ui'
import {NScrollbar} from 'naive-ui'

defineProps<{ msg: string }>()

const count = ref(6)
</script>

<template>
  <div class="sevtion has-text-centered">
  <h1>{{ msg }}</h1>
  <button class="button is-rounded is-primary" @click="count++">count is: {{ count }}</button>
 </div>
   <n-scrollbar class="section" style="max-height: 120px;">
    And as I sat there, brooding on the old unknown world, I thought of Gatsby’s
    wonder when he first picked out the green light at the end of Daisy’s dock. He
    had come a long way to this blue lawn and his dream must have seemed so close
    that he could hardly fail to grasp it. He did not know that it was already
    behind him, somewhere back in that vast obscurity beyond the city, where the
    dark fields of the republic rolled on under the night.<br /><br />

    Gatsby believed in the green light, the orgastic future that year by year
    recedes before us. It eluded us then, but that’s no matter—tomorrow we will
    run faster, stretch out our arms farther. . . . And one fine morning——<br /><br />

    So we beat on, boats against the current, borne back ceaselessly into the
    past.
  </n-scrollbar>
</template>

<style scoped>

</style>
