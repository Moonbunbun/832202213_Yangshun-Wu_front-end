<template>
  <div class="dashboard-container">
    <div class="dashboard-text">欢迎使用Sheep Contacts</div>
  </div>
</template>

<script>
import { mapGetters } from 'vuex'

export default {
  name: 'Dashboard',
  computed: {
    ...mapGetters([
      'name'
    ])
  }
}
</script>

<style lang="scss" scoped>
.dashboard {
  &-container {
    margin: 30px;
  }
  &-text {
    color: #767676;
    font-size: 30px;
    line-height: 46px;
  }
}
</style>
