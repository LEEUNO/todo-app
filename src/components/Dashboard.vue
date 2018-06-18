<template>
  <div class="Dashboard">
    <div class="section-item">
      <h4>Task</h4>
      <div>
        12
      </div>
    </div>
    <div class="section-item">
      <h4>Done</h4>
      <div>
        6
      </div>
    </div>
    <div class="section-item">
      <h4>Clear Rate</h4>
      <div>
        50%
      </div>
    </div>
  </div>
</template>

<script>

  export default {
    name: 'Dashboard',
    data () {
      return {
        listItem: []
      }
    }
  }
</script>
<style lang="scss" scoped>
.Dashboard {
  border: 1px solid #ddd;
  padding: 8px;
  display: flex;
  align-items: stretch;
  .section-item {
    flex-grow: 1;
    text-align: center;
    h4 {
      margin-bottom: 12px;
    }
  }
}
</style>
