<template>
    <div class="flex-center-column container">
        <h2>{{ title }}</h2>
        <video :src="video"></video>
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
video {
  width: 80vw;
}
</style>