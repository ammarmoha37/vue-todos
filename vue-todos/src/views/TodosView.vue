<script setup>
import TodoAdder from '../components/TodoAdder.vue';

</script>

<template>
  <main>
    <h1>Add Todo</h1>
    <TodoAdder></TodoAdder>
  </main>
</template>

<style lang="scss" scoped>
main {
  display: flex;
  flex-direction: column;
  max-width: 500px;
  width: 100%;
  margin: 0 auto;
  padding: 40px 16px;

  h1 {
    margin-bottom: 16px;
    text-align: center;
  }
}
</style>