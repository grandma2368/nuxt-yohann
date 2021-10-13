<template>
<!-- <div class="img">
    <img src="/img/photo-groupe-boxe-1.jpg" alt="photo groupe boxe 1">
</div> -->
<div id="slider">
  <figure>
    <img src="/img/photo-groupe-boxe-1.jpg" alt="photo groupe boxe 1">
    <img src="/img/photo-groupe-boxe-2.jpg" alt="photo groupe boxe 2">
    <img src="/img/photo-groupe-boxe-3.jpg" alt="photo groupe boxe 3">
  </figure>
</div>
</template>

<script>
export default {}
</script>

<style>
div#slider { width: 80%; max-width: 1000px; }
div#slider figure {
  position: relative;
  width: 500%;
  margin: 0;
  padding: 0;
  font-size: 0;
  left: 0;
  text-align: left;
  animation: 30s slidy infinite;
}
div#slider figure img { width: 20%; height: auto; float: left; }
div#slider { width: 80%; max-width: 1000px; overflow: hidden }
@keyframes slidy {
  0% { left: 0%; }
  20% { left: 0%; }
  25% { left: -100%; }
  45% { left: -100%; }
  50% { left: -200%; }
  70% { left: -200%; }
  75% { left: -300%; }
  95% { left: -300%; }
  100% { left: -300%; }
}
</style>