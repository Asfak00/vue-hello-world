<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <h3>A Front-End Web Developer</h3>

    <p>Play with this button</p>
    <button type="button" @click="count++">count is {{ count }}</button>
  </div>
</template>

<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
