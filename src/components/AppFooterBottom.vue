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
                        <img src="/img/footer-facebook.png">
                    </li>
                    <li>
                        <img src="/img/footer-twitter.png">
                    </li>
                    <li>
                        <img src="/img/footer-youtube.png">
                    </li>
                    <li>
                        <img src="/img/footer-pinterest.png">
                    </li>
                    <li>
                        <img src="/img/footer-periscope.png">
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
    padding: 50px 0;

    .container {
        display: flex;
        align-items: center;
        justify-content: space-between;

        button {
            all: unset;
            padding: 15px;
            text-transform: uppercase;
            font-weight: bold;
            border: 2px solid $banner-bg;
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
                gap: 20px;
            }
        }
    }
}
</style>
