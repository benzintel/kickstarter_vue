<template>
  <h1 class="title-name">{{titleName}}</h1>
</template>

<script>
export default {
  props: ['titleName']
}
</script>

<style scoped>
  .title-name {
    color: red;
  }
</style>

