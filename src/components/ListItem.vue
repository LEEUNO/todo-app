<template>
  <div class="ListItem">
    <h4>List Container</h4>
    <div class="list-wrapper">
      <ul>
        <li
          v-for="item in items"
          :key='item'>
          {{item}}
          <input type="checkbox" name="" value="">
        </li>
      </ul>
    </div>
  </div>
</template>

<script>

  export default {
    name: 'ListItem',
    data () {
      return {
        items: ['test', 'task2', 'task3', 'task3', 'task3', ]
      }
    }
  }
</script>
<style lang="scss" scoped>
.ListItem {
  margin-top: 12px;
  /* background-color: #ededed; */
  min-height: 300px;
  padding-bottom: 140px;
  .list-wrapper {
    ul {
      li {
        margin: 12px 0;
        line-height: 24px;
        background-color: white;
        padding: 12px;
        border: 1px solid #ededed;
        border-radius: 4px;
        input {
          float: right;
        }
      }
    }
  }
}
</style>
