<template>
  <div class="pixel"></div>
</template>

<script>
export default {
  name: 'Pixel',
  props: {
    msg: String
  }
}
</script>

<style scoped>
  .pixel { border: 1px solid lightgray;width:30px;height:30px;box-sizing: border-box; }
</style>
