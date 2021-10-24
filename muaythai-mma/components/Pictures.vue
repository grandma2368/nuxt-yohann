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
    border-radius: 20px;
    margin: 1%;
}
h2 {
    font-size: 2rem;
}
span {
    margin: 1%;
    font-size: 1.5rem;
}
</style>