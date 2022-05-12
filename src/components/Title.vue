<template>
  <h1>{{this.msg}}</h1>
</template>

<script>
export default {
  name: `Title`,
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">
h1 {
  color: palevioletred;
  background: rgba(255, 192, 203, 0.418);
}
</style>