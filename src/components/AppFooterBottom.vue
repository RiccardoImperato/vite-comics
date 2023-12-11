<script>
export default {}
</script> 

<template>
    <footer>
        <div class="container">
            <button>Sing-up now</button>
            <div>
                <span>Follow Us</span>
                <ul>
                    <li>
                        <a href="#">
                            <img src="/img/footer-facebook.png">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="/img/footer-twitter.png">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="/img/footer-youtube.png">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="/img/footer-pinterest.png">

                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="/img/footer-periscope.png">
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </footer>
</template>

<style scoped lang="scss">
@use '../styles/partials/variables' as *;

footer {
    background-color: $footer-bg;
    color: #fff;
    padding: 30px 0;

    .container {
        display: flex;
        align-items: center;
        justify-content: space-between;

        button {
            all: unset;
            cursor: pointer;
            padding: 15px;
            text-transform: uppercase;
            font-weight: bold;
            border: 2px solid transparent;

            &:hover {
                border: 2px solid $banner-bg;
            }
        }

        div {
            display: flex;
            align-items: center;

            span {
                margin: 0 20px;
                font-weight: bold;
                text-transform: uppercase;
                color: $banner-bg;
            }

            ul {
                all: unset;
                list-style-type: none;
                display: flex;
                flex-wrap: wrap;
                gap: 20px;

                a:hover {
                    filter: brightness(2);
                }
            }
        }
    }
}
</style>
