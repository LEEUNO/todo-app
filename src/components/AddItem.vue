<template>
  <div class="AddItem">
    <div class="input-box">
      <input type="text">
      <button type="button" name="button">Add list</button>
    </div>
  </div>
</template>

<script>

  export default {
    name: 'AddItem',
    data () {
      return {
        listItem: []
      }
    }
  }
</script>
<style lang="scss" scoped>
.AddItem {
  position: fixed;
  width: 100%;
  background-color: white;
  left: 0;
  bottom: 0;
  padding: 12px;
  .input-box {
    input {
      width: 100%;
      border: 1px solid #ededed;
      height: 36px;
      font-size: 16px;
      margin-bottom: 12px;
      padding: 0 12px;
    }
    button {
      width: 100%;
      font-size: 16px;
      background-color: black;
      color: white;
      padding: 12px;
    }
  }
}
</style>
