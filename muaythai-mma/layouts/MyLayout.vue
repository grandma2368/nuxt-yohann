<template>
  <div class="layout">
    <Header />
    <Carousel/>
    <div class="container">
      <nav>
        <nuxt-link to="/">Accueil</nuxt-link>
        <nuxt-link to="/about">A propos</nuxt-link>
        <nuxt-link to="/gallery">Photo</nuxt-link>
        <nuxt-link to="/videos">Video</nuxt-link>
      </nav>
    </div>
    <Nuxt />
    <Footer />
  </div>
</template>

<style lang="scss" scoped>
.layout {
  background-color: black;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-direction: row;
}
</style>