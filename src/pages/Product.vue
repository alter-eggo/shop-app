<template>
  <div class="wrapper-content wrapper-content--fixed">
    <section>
      <div class="container">
        <h1>Product: </h1>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  created() {
    //do something after creating vue instance
    console.log(this.$route);
  }
}
</script>

<style lang="scss" scoped>
</style>
