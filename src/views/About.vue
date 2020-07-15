<template>
  <div>
    <Title title="About Us" />
    <div>
      <Jumbotron />
      <Offers />
    </div>
  </div>
</template>

<script>
import Offers from "../components/About/Offers";
import Jumbotron from "../components/About/Jumbotron";
import Title from "../components/Shared/PageTitle";

export default {
  name: "About",
  components: {
    Offers,
    Jumbotron,
    Title
  }
};
</script>

<style scoped>
.aboutTitle {
  font-size: 20px;
}

.card {
  border: none;
}
</style>
