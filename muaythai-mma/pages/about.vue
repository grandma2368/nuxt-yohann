<template>
  <div class="flex-center-column container">
    <h2>Yohann Recourse</h2>
    <span><b>Facebook :</b> lien de ta page</span>
    <span><b>Instagram :</b> lien de ta page</span>
    <span><b>Mail :</b> muaythai1985@hotmail.fr</span>
  </div>
</template>

<script>
export default {
    name:"about",
    layout (context) {
        return "MyLayout"
    }
}
</script>

<style lang="scss" scoped>
div {
  width: 100%;
}
span {
  margin: 1%;
  font-size: 1.5rem;
}
</style>