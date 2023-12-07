<script>
export default {}
</script> 

<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="/img/dc-logo.png" alt="">
            </div>
            <ul>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>Tv</li>
                <li>Games</li>
                <li>Collectibles</li>
                <li>Videos</li>
                <li>Fans</li>
                <li>News</li>
                <li>Shop</li>
            </ul>
        </div>
    </header>
</template>

<style scoped lang="scss">
@use '../styles/partials/variables' as *;

header {
    color: #464646;
    background-color: $header-bg;

    .container {
        display: flex;
        justify-content: space-between;

        .logo {
            padding: 10px 0;
        }

        img {
            height: 80px;
            display: block;
        }
    }
}

ul {
    all: unset;
    list-style-type: none;
    display: flex;
    gap: 30px;

    li {
        line-height: 80px;
        cursor: pointer;
        font-weight: bold;
        text-transform: uppercase;
        font-size: 12px;
        border-top: 5px solid transparent;
    }

    li:hover {
        color: $banner-bg;
        border-bottom: 5px solid $banner-bg;
    }
}
</style>
