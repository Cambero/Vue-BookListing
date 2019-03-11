<template lang="html">
  <h1>{{ title }}</h1>
</template>

<script>
export default {
  name: 'BookList',
  data() {
    return {
      title: 'All Books'
    }
  }
}
</script>

<style lang="css" scoped>
  h1, h2 {
    font-weight: normal;
  }
</style>
