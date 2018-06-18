<template>
  <div class="Home">
    <h1>Home</h1>
    <list-item></list-item>
    <add-item></add-item>
  </div>
</template>

<script>
  import ListItem from './ListItem'
  import AddItem from './AddItem'
  export default {
    name: 'Home',
    data () {
      return {
      }
    },
    components: {
      ListItem,
      AddItem
    }
  }
</script>
<style lang="scss" scoped>
.Home {
  padding: 0 12px;
  padding-top: 52px;
}
</style>
