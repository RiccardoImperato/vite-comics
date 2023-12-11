<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooterTop from './components/AppFooterTop.vue';
import AppFooterBottom from './components/AppFooterBottom.vue';
import AppBanner from './components/AppBanner.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooterTop,
    AppFooterBottom,
    AppBanner,
  }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppBanner />
  <AppFooterTop />
  <AppFooterBottom />
</template>

<style lang="scss">
@use './styles/partials/variables' as *;
@use './styles/general.scss' as *;
</style>
