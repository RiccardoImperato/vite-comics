<script>
export default {}
</script> 

<template>
    <div class="bg">
        <div class="container">
            <div class="list">
                <div>
                    <ul>
                        <li>
                            <h3>Dc comics</h3>
                        </li>
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
                    <div>
                        <ul>
                            <li>
                                <h3>Shop</h3>
                            </li>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>
                </div>
                <div>
                    <ul>
                        <li>
                            <h3>Dc</h3>
                        </li>
                        <li>Terms Of Use</li>
                        <li>Privacy policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                <div>
                    <ul>
                        <li>
                            <h3>Site</h3>
                        </li>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Univers</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
            </div>

            <div class="logo-bg">
                <img src="/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use '../styles/partials/variables' as *;

.bg {
    color: #fff;
    background-image: url(/img/footer-bg.jpg);
    background-size: cover;
    overflow: hidden;

    .container {
        display: flex;
        justify-content: space-between;
    }

    .logo-bg {
        width: 50%;
        position: relative;

        img {
            width: 100%;
            position: absolute;
            left: 0;
            top: -100px;
        }
    }

    .list {
        display: flex;
        gap: 50px;
        padding: 30px 0;

        ul {
            margin-bottom: 25px;
            list-style-type: none;
            color: #959595;
            font-size: 14px;

            h3 {
                color: #fff;
                text-transform: uppercase;
                margin-bottom: 20px;
            }

            li {
                margin: 8px 0;
            }
        }
    }
}
</style>
