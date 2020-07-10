<template>
  <div id="app" class="w-100 d-flex flex-wrap flex-column">
    <Navbar />
    <router-view class="container" />
    <Footer class="mt-auto" />
  </div>
</template>

<script>
import Navbar from "./components/Navbar";
import Footer from "./components/Footer";
export default {
  name: "app",
  components: {
    Navbar,
    Footer,
  },
};
</script>

<style>
#app {
  position: relative;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  min-height: 100vh;
  min-width: 100vw;
}
</style>
