<template>
  <div>
    <p @click="count++">{{ count }}</p>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  data() {
    return {
      count: 10
    }
  }
}
</script>

<style lang="less" scoped></style>
