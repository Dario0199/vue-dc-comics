<template>
  <section class="hero">
      <div class="title-card">
          <h4>current series</h4>
      </div>
  </section>
</template>

<script>
export default {
    name: 'Hero'
}
</script>

<style scoped lang="scss">
    section{
        background-image: url('../assets/jumbotron.jpg');
        width: 100%;
        height: 320px;
        background-size: cover;
        position: relative;

        .title-card{
            text-transform: uppercase;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            width: 150px;
            height: 35px;
            position: absolute;
            left: 155px;
            bottom: -18px;
            background: #0c7cec;
        }
    }
    
</style>