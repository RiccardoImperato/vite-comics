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
                <li>
                    <a href="#">Characters</a>
                </li>
                <li>
                    <a href="#">Comics</a>
                </li>
                <li>
                    <a href="#">Movies</a>
                </li>
                <li>
                    <a href="#">Tv</a>
                </li>
                <li>
                    <a href="#">Games</a>
                </li>
                <li>
                    <a href="#">Collectibles</a>
                </li>
                <li>
                    <a href="#">Videos</a>
                </li>
                <li>
                    <a href="#">Fans</a>
                </li>
                <li>
                    <a href="#">News</a>
                </li>
                <li>
                    <a href="#">Shop</a>
                </li>
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
    flex-wrap: wrap;
    gap: 30px;

    li {
        line-height: 80px;
        cursor: pointer;
        font-weight: bold;
        text-transform: uppercase;
        font-size: 12px;
        border-top: 5px solid transparent;

        &:hover {
            color: $banner-bg;
            border-bottom: 5px solid $banner-bg;
        }
    }
}
</style>
