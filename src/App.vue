<script>
// Header
import AppHeader from './components/AppHeader.vue';
// Jumborton
import Jumbo from './components/Jumbo.vue';
// Main
import AppMain from './components/AppMain.vue';
// Banner 
import AppBanner from './components/AppBanner.vue';
//Footer
import AppFooterTop from './components/AppFooterTop.vue';
import AppFooterBottom from './components/AppFooterBottom.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooterTop,
    AppFooterBottom,
    AppBanner,
    Jumbo
  }
}
</script>

<template>
  <AppHeader />
  <Jumbo />
  <AppMain />
  <AppBanner />
  <AppFooterTop />
  <AppFooterBottom />
</template>