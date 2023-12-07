<script>
export default {}
</script> 

<template>
    <header>
        <div class="container">
            <div>
                <img src="/img/dc-logo.png" alt="">
            </div>
            <ul>
                <li>menu</li>
                <li>menu</li>
                <li>menu</li>
                <li>menu</li>
                <li>menu</li>
                <li>menu</li>
                <li>menu</li>
                <li>menu</li>
                <li>menu</li>
                <li>menu</li>
            </ul>
        </div>
    </header>
</template>

<style scoped lang="scss">
@use '../styles/partials/variables' as *;

header {
    padding: 10px 0;
    background-color: $header-bg;

    img {
        width: 80px;
        display: block;
    }
}

ul {
    all: unset;
    list-style-type: none;
    display: flex;

    li {
        padding: 25px 15px;
    }
}
</style>
