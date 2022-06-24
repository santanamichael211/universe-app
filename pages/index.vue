<template>
  <div class="universe-app">
    <Nav/>
    <ToolBar/>
  </div>
</template>


<style lang="scss">
  .universe-app {
    background-color: #999;
    font-family: 'Roboto', sans-serif;
  }
</style>

<script>
import Nav from '../components/layout/Nav.vue'
import ToolBar from '../components/layout/ToolBar.vue'

export default {
  components: { Nav, ToolBar },
  name: 'UniverseApp'
}
</script>
