<template>
  <div class="todo-list">
    todo list
    <div v-for="(item, id) in items" :key="id">
      <list-item :item="item" :id="id" @clicked="boolSwitch" />
    </div>
  </div>
</template>

<script>

</script>

<style>

</style>