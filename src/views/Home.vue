<template>
  <div class="home">
    <Carousel />
    <About />
  </div>
</template>

<script>
import Carousel from "../components/Home/Carousel";
import About from "../components/Home/About";

export default {
  name: "Home",
  components: {
    Carousel,
    About
  }
};
</script>
<style scoped>
</style>
