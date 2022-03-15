<template>
    <div class="card">
        <figure>
            <img :src="img" alt="">
            <figcaption>{{ series }}</figcaption>
        </figure>
    </div>
</template>

<script>
export default {
    props: {
        img: String,
        series: String,
    }
}
</script>

<style lang="scss" scoped>

.card {
    width: calc((100% - 50px) / 6);
    flex-grow: 1;

    figure {
        width: 100%;
        aspect-ratio: 1;

        img {
            height: 100%;
            object-fit: cover;
            object-position: top center;
        }
    }
}

</style>