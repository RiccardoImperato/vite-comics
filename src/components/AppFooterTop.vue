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
                    <div>
                        <ul>
                            <li>
                                <h3>Shop</h3>
                            </li>
                            <li>
                                <a href="#">Shop DC</a>
                            </li>
                            <li>
                                <a href="#">Shop DC Collectibles</a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div>
                    <ul>
                        <li>
                            <h3>Dc</h3>
                        </li>
                        <li>
                            <a href="#">Terms Of Use</a>
                        </li>
                        <li>
                            <a href="#">Privacy policy (New)</a>
                        </li>
                        <li>
                            <a href="#">Ad Choices</a>
                        </li>
                        <li>
                            <a href="#">Advertising</a>
                        </li>
                        <li>
                            <a href="#">Jobs</a>
                        </li>
                        <li>
                            <a href="#">Subscriptions</a>
                        </li>
                        <li>
                            <a href="#">Talent Workshops</a>
                        </li>
                        <li>
                            <a href="#">CPSC Certificates</a>
                        </li>
                        <li>
                            <a href="#">Ratings</a>
                        </li>
                        <li>
                            <a href="#">Shop Help</a>
                        </li>
                        <li>
                            <a href="#">Contact Us</a>
                        </li>
                    </ul>
                </div>
                <div>
                    <ul>
                        <li>
                            <h3>Site</h3>
                        </li>
                        <li>
                            <a href="#">DC</a>
                        </li>
                        <li>
                            <a href="#">MAD Magazine</a>
                        </li>
                        <li>
                            <a href="#">DC Kids</a>
                        </li>
                        <li>
                            <a href="#">DC Univers</a>
                        </li>
                        <li>
                            <a href="#">DC Power Visa</a>
                        </li>
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
    background-image: url(../assets/img/footer-bg.jpg);
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
            top: -75px;
        }
    }

    .list {
        display: flex;
        gap: 50px;
        padding: 30px 0;

        ul {
            all: unset;
            list-style-type: none;
            margin-bottom: 25px;
            color: #959595;
            font-size: 14px;

            h3 {
                color: #fff;
                text-transform: uppercase;
                margin: 20px 0;
            }

            li {
                margin: 8px 0;

                a:hover {
                    filter: brightness(2);
                }
            }
        }
    }
}
</style>
