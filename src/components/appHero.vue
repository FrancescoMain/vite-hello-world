<script>
export default {
    data() {
        return {
            img: "./public/img/jumbo.png",
        };
    }
}

</script>

<template>
    <div>
        <img :src="img" alt="jumbo">
    </div>
</template>

<style scoped>
img {
    max-width: 100%;
}
</style>
