<template>
  <div class="home">
    <img alt="WW logo" src="../assets/Wonder-Woman-banner_200107_115242.png">
    <HelloWorld msg="This is My Bad Ass Page. I Can Do All Things."/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
