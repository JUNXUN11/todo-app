<script setup>
import { RouterView } from 'vue-router'
import TodoAppHeader from './components/TodoHeader.vue'

</script>

<template>
 <todo-app-header />
  <RouterView />
</template>

<style lang="scss">

@import url("https://fonts.googleapis.com/css2?family=Rubik:wght@300;400;500;700&display=swap");

* {
  font-family: "Rubik", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
}

</style>
