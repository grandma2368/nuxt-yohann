<template>
    <agile :autoplay="true" :autoplay-speed="5000" :dots="false" :infinite="true" :mobile-first="true" :nav-buttons="true" :pause-on-hover="true" :slides-to-show="1" class="test">
        <div>
            <img class="image" src="/img/photo-groupe-boxe-1-test.png" alt="photo groupe boxe 1">
        </div>
        <div>
            <img class="image" src="/img/photo-groupe-boxe-2-test.png" alt="photo groupe boxe 2">
        </div>
        <div>
            <img class="image" src="/img/photo-groupe-boxe-3-test.png" alt="photo groupe boxe 3">
        </div>
        <template slot="prevButton"><img class="arrow left" src="/img/left-facing-fist-apple.png" alt="poing gauche"></template>
        <template slot="nextButton"><img class="arrow right" src="/img/right-facing-fist-apple.png" alt="poing droit"></template>
    </agile>
</template>

<script>
export default {
    name: 'Carousel'
}
</script>

<style lang="scss">

.test {
    max-width: 80vw;
    margin: 0 auto;
}

.image {
    width: 80vw;
    margin: 0 auto;
    border-radius: 20px;
}

.arrow {
    width: 40%;
    position: relative;
}

.left {
    bottom: 50vh;
    left: -10vw;
}

.right {
    bottom: 50vh;
    right: -10vw;
}
</style>