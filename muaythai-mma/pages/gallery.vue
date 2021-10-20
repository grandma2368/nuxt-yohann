<template>
  <div class="container">
      <Pictures title="Test 1" img="/img/photo-groupe-boxe-1.png" desc="Photo numero 1 du groupe de boxeurs" />
      <Pictures title="Test 2" img="/img/photo-groupe-boxe-2.png" desc="Photo numero 2 du groupe de boxeurs" />
      <Pictures title="Test 3" img="/img/photo-groupe-boxe-3.png" desc="Photo numero 3 du groupe de boxeurs" />
  </div>
</template>

<script>
export default {
    name:"gallery",
    layout (context) {
        return "MyLayout"
    }
}
</script>

<style lang="scss" scoped>

</style>