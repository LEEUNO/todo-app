<template>
  <div class="MainHeader">
    <h4>Main Header</h4>
  </div>
</template>

<script>
  export default {
    name: 'Hello',
    data () {
      return {
        msg: 'Main Header'
      }
    }
  }
</script>
<style lang="scss" scoped>
.MainHeader {
  position: fixed;
  display: flex;
  align-items: center;
  top: 0;
  width: 100%;
  height: 52px;
  padding: 0 12px;
  background-color: #ededed;
  h4 {

  }
}
</style>
