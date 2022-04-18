<template>
  <div>{{ state }}</div>
  <el-button plain @click="add">add</el-button>
</template>

<script setup>
import { ref } from "vue";
const state = ref(1);

/**
 * add
 */
const add = () => {
  state.value++;
};
</script>
