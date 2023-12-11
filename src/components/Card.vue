<script>
export default {
    props: {
        img: String,
        title: String
    }
}
</script>

<template>
    <div class="card">
        <div>
            <img :src="img">
        </div>
        <div class="title">{{ title }}</div>
    </div>
</template>

<style scoped lang="scss">
.card {
    cursor: pointer;
    width: calc(100% / 6);
    padding: 10px 15px;

    &:hover .title {
        filter: brightness(2);
    }

    img {
        height: 180px;
        width: 100%;
        object-fit: cover;
        object-position: top center;
    }

    .title {
        color: #959595;
        padding: 10px 0;
        text-transform: uppercase;
        font-size: 12px;
    }
}
</style>
