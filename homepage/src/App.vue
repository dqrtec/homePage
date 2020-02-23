<template>
  <div id="app">
    <div>
      <Menu></Menu>
      <router-view/>
    </div>
  </div>
</template>

<script>
import Menu from './components/Menu.vue'

export default {
  name: 'App',
  components: {
    Menu
  }
}
</script>

<style>

</style>