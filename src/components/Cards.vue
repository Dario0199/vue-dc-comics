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

img{
  width: 100%;
  height: 200px;
  object-fit: cover;
  object-position: top;
}
P{
  text-transform: uppercase;
  font-size: 14PX;
  margin-top: 10px;
}
</style>