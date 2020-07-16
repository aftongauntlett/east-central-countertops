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
    <div class="pt-5">
      <Title title="About Us" />
    </div>
    <Jumbotron :home="true" />

    <Title title="Contact Us" />
    <div class="d-flex justify-content-around flex-wrap">
      <Form />
      <Info />
    </div>
    <Title title="Find Us" />

    <Map />
  </div>
</template>

<script>
import Carousel from "../components/Home/Carousel";
import Form from "../components/Contact/Form";
import Jumbotron from "../components/About/Jumbotron";
import Info from "../components/Contact/Info";
import Map from "../components/Contact/Map";
import Title from "../components/Shared/PageTitle";

export default {
  name: "Home",
  components: {
    Carousel,
    Form,
    Jumbotron,
    Info,
    Map,
    Title
  }
};
</script>
<style scoped>
.bg-info {
  background-color: white !important;
  border: none !important;
}

.jumbotron {
  margin-top: 20px;
  margin-bottom: unset !important;
  padding: 20px;
  background-color: white !important;
  border: none !important;
}

>>> .carousel-caption {
  background-color: rgba(44, 43, 43, 0.493);
  border-radius: 12px;
}

@media only screen and (min-width: 300px) {
  .display-3 {
    font-family: "Marcellus", serif;
    font-size: 35px;
    color: rgb(26, 104, 26);
  }

  .lead {
    font-size: 15px;
    color: rgb(26, 104, 26);
    font-family: "Montserrat", sans-serif;
  }
}

@media only screen and (min-width: 600px) {
  .display-3 {
    font-family: "Marcellus", serif;
    color: rgb(26, 104, 26);
    font-size: 55px;
  }

  .lead {
    color: rgb(26, 104, 26);
    font-size: 25px;
    font-family: "Montserrat", sans-serif;
  }
}
</style>
