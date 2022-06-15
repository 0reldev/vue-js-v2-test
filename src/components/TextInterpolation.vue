<template>
  <div class="text-interpolation">
    <hr>
    <h2>Text interpolation</h2>
    {{ message }}
  </div>
</template>

<script>
export default {
  name: 'TextInterpolation',
  props: {
    message: String
  }
}
</script>

<style scoped>
.text-interpolation {
  margin: 5em 0;
}
</style>
