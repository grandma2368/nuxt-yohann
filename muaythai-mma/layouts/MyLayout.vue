<template>
  <div class="layout">
    <Carousel/>
    <div class="container">
      <nav>
        <div>
          <nuxt-link to="/">Accueil</nuxt-link>
        </div>
        <div>
          <nuxt-link to="/about">A propos</nuxt-link>
        </div>
        <div>
          <nuxt-link to="/gallery">Photo</nuxt-link>
        </div>
        <div>
          <nuxt-link to="/videos">Video</nuxt-link>
        </div>
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
  position: relative;
  bottom: 8vh;
  div {
    background-color: rgb(71, 71, 71);
    border-radius: 20px;
    box-shadow: 10px 5px 5px rgb(116, 114, 114);
    a {
      padding: 1vw;
    }
    padding: 1vw 0;
    margin: 0 2.5vw;
  }
}
</style>