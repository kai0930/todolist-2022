<script setup>
import { ref } from "vue";

const items = ref([
  { name: "買い物", condition: "undone" },
  { name: "歯医者", condition: "done" },
]);
const newTaskName = ref("");
const newTaskCondition = ref(0);
</script>

<template>
  <div>Todolist</div>
  <div v-for="item in items" :key="item.name">
    <div class="name">名前:</div>
  </div>
</template>

<style></style>
