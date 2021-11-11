<template>
  <div id="app">
    <SiteHeader />
    <SiteMain />
    <SiteFooter />
  </div>
</template>

<script>
import SiteHeader from "./components/SiteHeader.vue";
import SiteMain from "./components/SiteMain.vue";
import SiteFooter from "./components/SiteFooter.vue";

export default {
  name: "App",
  components: {
    SiteHeader,
    SiteMain,
    SiteFooter,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/variables.scss";
@import "./assets/scss/common.scss";
@import url("https://fonts.googleapis.com/css2?family=Acme&family=Roboto:wght@300;400;500&display=swap");

#app {
  font-family: "Roboto", Helvetica, Arial, sans-serif;
}
</style>
