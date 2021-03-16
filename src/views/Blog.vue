<template>
  <div class="blog">
    <todo-list />
  </div>
    
</template>

<script>
import TodoList from '../components/TodoList.vue'
export default {
  name: 'blog',
  components: { 
    TodoList
  }   
}
</script>

<style>

</style>