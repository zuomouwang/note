<template>
  <div>
    <p @click="count++">{{ count }}</p>
    <LunboTu></LunboTu>
  </div>
</template>

<script>
import LunboTu from '../components/lunbo/LunboTu.vue'
export default {
  name: 'HomePage',
  data() {
    return {
      count: 10
    }
  },
  components: {
    LunboTu
  }
}
</script>

<style lang="less" scoped></style>
