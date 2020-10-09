<template>
  <NavBar />
  <LandingPage />
</template>

<script>
import NavBar from "./components/NavBar.vue";
import LandingPage from "./components/LandingPage";

export default {
  name: "App",
  components: {
    NavBar,
    LandingPage,
  },
};
</script>