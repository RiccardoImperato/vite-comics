<script>
import Comics from './Comics.vue';
import "@fontsource/open-sans";
import "@fontsource/open-sans/400.css";

export default {
    components: {
        Comics
    }
}
</script> 

<template>
    <main>
        <div class="container">
            <div class="series badge">Current series</div>
            <Comics />
            <div class="more">
                <button class="badge">Load more</button>
            </div>
        </div>
    </main>
</template>

<style scoped lang="scss">
@use '../styles/partials/variables' as *;

main {
    background-color: $main-bg;
    color: #fff;
    padding: 30px 0;

    .container {
        position: relative;

        .badge {
            all: unset;
            font-weight: bold;
            text-transform: uppercase;
            color: #fff;
            background-color: $banner-bg;
        }

        .series {
            font-size: 20px;
            padding: 10px 30px;
            position: absolute;
            top: -60px;

        }

        .more {
            text-align: center;
            margin-top: 20px;

            button {
                cursor: pointer;
                font-size: 14px;
                padding: 12px 50px;
            }
        }
    }
}
</style>
