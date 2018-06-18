<template>
  <div class="ListItem">
    <h4>List Container</h4>
    <div class="list-wrapper">
      <ul>
        <li></li>
      </ul>
    </div>
  </div>
</template>

<script>

  export default {
    name: 'ListItem',
    data () {
      return {
        listItem: []
      }
    }
  }
</script>
<style lang="scss" scoped>
.ListItem {
  .list-wrapper {
  }
}
</style>
