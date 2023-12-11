<script>
import Comics from './Comics.vue';

export default {
    components: {
        Comics
    }
}
</script> 

<template>
    <main>
        <Comics />
    </main>
</template>

<style scoped lang="scss">
@use '../styles/partials/variables' as *;

main {
    background-color: $main-bg;
    color: #fff;
    padding: 30px 0;
}
</style>
