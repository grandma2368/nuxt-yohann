<template>
  <div class="flex-center-column container">
    <span>
      Combattant professionnel formé par
      <b>suchin kanjanasuwan</b>
    </span>
    <span>
      plusieurs fois champion du
      <b>Lumpini Stadium</b>
      et champion de Thaïlande,
    </span>
    <span>
      formé par 
      <b>Mathieu nicourt</b>
      multiple Champion pionnier du MMA français,
    </span>
    <span>
      formé par
      <b>monsieur Fernand Lopez  Owonyebe</b>
    </span>
    <span>
      grand champion l'un des meilleurs coachs mondiaux et des plus grosses organisations telles que
      <b>l'UFC,</b>
    </span>
    <span>
      formé par
      <b>Nicolas Régnier</b>
      5e dan de luta livre.
    </span>
    <span>
      J'ai été moi-même
      <b>coach professionnel de MMA et Muaythai à la NR fight</b>
      pendant 5 ans.
    </span>
    <span>
      De retour sur le Caillou pour former les futurs combattant.e.s caledonien.ne.s.
    </span>
    <video src="/video/pres_yohann.mp4"></video>
  </div>
</template>

<script>
import Carousel from '../components/Carousel.vue'
export default {
  components: { Carousel },
  layout (context) {
    return "MyLayout"
  }
}
</script>

<style lang="scss" scoped>
video {
  margin: 1%;
  width: 80vw;
}
span {
  margin: 1%;
  font-size: 1.5rem;
}
</style>