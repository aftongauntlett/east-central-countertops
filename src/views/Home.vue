<template>
  <div>
    <b-jumbotron bg-variant="info" text-variant="black" border-variant="dark">
      <template v-slot:header>East Central Countertops and Cabinets</template>

      <template v-slot:lead>
        Building custom cabinets and laminate countertops in East Central
        Minnesota
      </template>
      <hr class="my-4" />
    </b-jumbotron>

    <Carousel />
    <Jumbotron />
    <Button />
    <Form />
    <Info />
    <Map />
  </div>
</template>

<script>
import Carousel from "../components/Home/Carousel";
import Form from "../components/Contact/Form";
import Jumbotron from "../components/About/Jumbotron";
import Button from "../components/About/Button";
import Info from "../components/Contact/Info";
import Map from "../components/Contact/Map";

export default {
  name: "Home",
  components: {
    Carousel,
    Form,
    Jumbotron,
    Button,
    Info,
    Map
  }
};
</script>
<style scoped>
.bg-info {
  background-color: white !important;
  border: none !important;
}

.jumbotron {
  padding-bottom: 10px;
  margin-bottom: unset !important;
  background-color: white !important;
  border: none !important;
}

.display-3 {
  font-family: "Charm", cursive;
  font-size: 75px;
}

.lead {
}
</style>
