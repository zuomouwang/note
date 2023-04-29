<template>
  <div>
    <p @click="count++">{{ count }}</p>
    <add-count></add-count>
  </div>
</template>

<script>
import addCount from '../components/zxw/addCount.vue'
export default {
  name: 'HomePage',
  data() {
    return {
      count: 10
    }
  },
  components: {
    addCount
  }
}
</script>

<style lang="less" scoped></style>
