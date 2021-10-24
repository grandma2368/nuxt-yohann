<template>
    <div class="flex-center-column container">
        <h2>{{ title }}</h2>
        <video :src="video" controls preload></video>
        <span>{{ desc }}</span>
    </div>
</template>

<script>
export default{
    name: "Video",
    props: {
        title: String,
        video: String,
        desc: String
    }
}
</script>

<style lang="scss" scoped>
div {
    width: 100%;
}
video {
  margin: 1%;
  width: 80vw;
}
</style>