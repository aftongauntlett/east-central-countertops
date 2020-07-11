<template>
  <b-jumbotron
    class="jumbotron"
    bg-variant="info"
    text-variant="black"
    border-variant="dark"
  >
    <template v-slot:header>Contact Us</template>
    <hr class="my-4" />
    <div class="contact">
      <div class="d-flex justify-content-around flex-wrap">
        <Form />
        <Info />
        <Map />
      </div>
    </div>
  </b-jumbotron>
</template>

<script>
import Form from "../components/Contact/Form";
import Map from "../components/Contact/Map";
import Info from "../components/Contact/Info";

export default {
  name: "Contact",
  components: {
    Form,
    Info,
    Map,
  },
};
</script>

<style scoped>
.jumbotron {
  padding-bottom: 10px;
  margin-bottom: unset !important;
  background-color: white !important;
  border: none !important;
}
</style>
