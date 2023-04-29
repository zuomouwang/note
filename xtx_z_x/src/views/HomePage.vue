<template>
  <div>
    <p @click="count++">{{ count }}</p>
    <LunboTu></LunboTu>
    <add-count></add-count>
  </div>
</template>

<script>
import LunboTu from '../components/lunbo/LunboTu.vue'
import addCount from '../components/zxw/addCount.vue'
export default {
  name: 'HomePage',
  data() {
    return {
      count: 10
    }
  },
  components: {
    LunboTu,
    addCount
  }
}
</script>

<style lang="less" scoped></style>
