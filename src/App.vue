<script setup>
import {reactive} from "vue";

const data = reactive({
  message:"",
  date:new Date(),
});

data.message = 'Hello, Vue3!!!';
</script>

<template>
  <div>{{data.message}}</div>
  <div>今日は{{data.date}}ですね。</div>
</template>

<style scoped>
</style>
