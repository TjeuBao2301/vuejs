<script setup lang="ts">
import TodoList from '../components/TodoList.vue'
import TodoForm from '../components/TodoForm.vue'
import TodoItem from '../components/TodoItem.vue'
</script>

<template>
  <main>
    <TodoList msg="Đây là một mục todo" />
    <TodoForm />
    <TodoItem/>
  </main>
</template>
