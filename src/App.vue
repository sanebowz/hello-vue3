<script setup>
import {reactive} from "vue";

const data = reactive({
  message:'',
})

data.message = 'Hello, Vue3!!!'
</script>

<template>
  <div>{{data.message}}</div>
</template>

<style scoped>
</style>
