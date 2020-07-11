<template>
  <div>
    <div>
      <Jumbotron />
      <Offers />
    </div>
  </div>
</template>

<script>
import Offers from "../components/About/Offers";
import Jumbotron from "../components/About/Jumbotron";

export default {
  name: "About",
  components: {
    Offers,
    Jumbotron,
  },
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
