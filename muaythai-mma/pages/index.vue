<template>
  <div class="container">
    <Header />
    <Carousel/>
    <Footer />
  </div>
</template>

<script>
export default {
  layout (context) {
    return "MyLayout"
  }
}
</script>

<style lang="scss" scoped>
h1 {
  color: rgb(248, 132, 0);
  margin: 1vh auto;
}
</style>