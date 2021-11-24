<template>
  <div>
    <img :src="url" :alt="title">
    <p>{{ title }}</p>
  </div>
</template>

<script>
export default {
    name: 'Cards',
    props: {
      url: String,
      title: String,
    }
}
</script>

<style scoped lang="scss">

</style>