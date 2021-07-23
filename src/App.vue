<template>
  <div id="app">
    <AppNav></AppNav>
    <AppMovies></AppMovies>
    <AppFooter></AppFooter>
  </div>
</template>

<script>
import AppNav from "./components/layouts/AppNav.vue";
import AppFooter from "./components/layouts/AppFooter.vue";
import AppMovies from "./components/Movies/AppMovies.vue";
export default {
  name: "App",
  components: {
    AppNav,
    AppFooter,
    AppMovies,
  },
};
</script>
