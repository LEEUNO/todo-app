<template>
  <div class="Home">
    <dashboard></dashboard>
    <list-item></list-item>
    <add-item></add-item>
  </div>
</template>

<script>
  import ListItem from './ListItem'
  import AddItem from './AddItem'
  import Dashboard from './Dashboard'

  export default {
    name: 'Home',
    data () {
      return {
      }
    },
    components: {
      ListItem,
      AddItem,
      Dashboard
    }
  }
</script>
<style lang="scss" scoped>
.Home {
  /* padding: 0 12px; */
  padding-top: 52px;
}
</style>
