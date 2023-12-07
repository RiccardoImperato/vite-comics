<script>
export default {}
</script> 

<template>
    <div class="banner">
        <div class="container">
            <ul>
                <li>
                    <img src="/img/buy-comics-digital-comics.png">
                    <span>
                        Digital comics
                    </span>
                </li>
                <li>
                    <img src="/img/buy-comics-merchandise.png">
                    <span>Dc merchandise</span>
                </li>
                <li>
                    <img src="/img/buy-comics-subscriptions.png">
                    <span>Subscription</span>
                </li>
                <li>
                    <img src="/img/buy-comics-shop-locator.png">
                    <span>Comic Shop locator</span>
                </li>
                <li>
                    <img src="/img/buy-dc-power-visa.svg">
                    <span>Dc power visa</span>
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

            span {
                margin-left: 15px;
            }
        }
    }


}
</style>
