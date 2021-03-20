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

const id = [1, 2, 3];
    const post= {
      id: 1,
      title: `How did you Taekwon-do that???`,
      date: `March 14, 2021`
    };

</script>

<style>

</style>