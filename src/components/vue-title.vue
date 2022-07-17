<template>
  <h1 class="vue-title">{{ msg }}</h1>
</template>

<script>
export default {
  data() {
    return {
      msg: 'Olar Vue!',
    }
  },
}
</script>

<style>
.vue-title {
  color: green;
}
</style>