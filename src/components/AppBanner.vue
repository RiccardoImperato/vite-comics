<script>
export default {}
</script> 

<template>
    <div class="banner">
        <div class="container">
            <ul>
                <li>
                    <img src="/img/buy-comics-digital-comics.png">
                    <a href="#">
                        Digital comics
                    </a>
                </li>
                <li>
                    <img src="/img/buy-comics-merchandise.png">
                    <a href="#">Dc merchandise</a>
                </li>
                <li>
                    <img src="/img/buy-comics-subscriptions.png">
                    <a href="#">Subscription</a>
                </li>
                <li>
                    <img src="/img/buy-comics-shop-locator.png">
                    <a href="#">Comic Shop locator</a>
                </li>
                <li>
                    <img src="/img/buy-dc-power-visa.svg">
                    <a href="#">Dc power visa</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use '../styles/partials/variables' as *;

.banner {
    background-color: $banner-bg;
    color: #fff;
    padding: 50px 0;

    .container {
        padding: 0 40px;

        ul {
            all: unset;
            list-style-type: none;
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
        }

        li {
            display: flex;
            align-items: center;
            font-size: 12px;
            text-transform: uppercase;

            img {
                object-fit: contain;
                width: 50px;
                height: 50px;
            }

            a {
                margin-left: 15px;
            }
        }
    }
}
</style>
