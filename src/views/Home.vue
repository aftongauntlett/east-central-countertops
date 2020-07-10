<template>
  <div class="home">
    <Carousel />
    <About />
    <Form />
  </div>
</template>

<script>
import Carousel from "../components/Home/Carousel";
import About from "./About";
import Form from "../components/Contact/Form";

export default {
  name: "Home",
  components: {
    Carousel,
    About,
    Form,
  },
};
</script>
<style scoped></style>
