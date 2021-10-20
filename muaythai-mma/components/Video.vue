<template>
    <div class="flex-center container">
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

</style>