<template>
    <div class="flex-center-column container">
        <h2>{{ title }}</h2>
        <img :src="img" :alt="title">
        <span>{{ desc }}</span>
    </div>
</template>

<script>
export default{
    name: "Pictures",
    props: {
        title: String,
        img: String,
        desc: String
    }
}
</script>

<style lang="scss" scoped>
img {
    width: 80%;
}
</style>