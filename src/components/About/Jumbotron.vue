<template>
  <div>
    <p class="aboutInfo">
      Gary Klein started East Central Countertops 13 years ago, and has 39
      years of experience building countertops and cabinets in Mora, MN.
      He is known for his attention to detail and demands the highest
      quality, from the parts you see every day to the parts you'll never
      see. Those years of experience have taught him what works and what
      doesn't, so you can be confident that your custom kitchen or
      bathroom will last for many years to come.
    </p>
    <Button v-if="home" />
  </div>
</template>

<script>
import Button from "./Button";

export default {
  name: "Jumbotron",
  components: {
    Button
  },
  props: ["home"]
};
</script>

<style scoped>
.aboutTitle {
  font-size: 20px;
}

.card {
  border: none;
}

.bg-info {
  background-color: white !important;
  border: none !important;
}

.jumbotron {
  margin-top: 20px;
  padding-bottom: 10px;
  margin-bottom: unset !important;
  background-color: white !important;
  border: none !important;
}

.aboutInfo {
  padding: 20px;
  border-radius: 12px;
  margin: 20px;
  font-size: 18px;
  font-family: "Montserrat", sans-serif;
  background-color: rgba(98, 126, 98, 0.185);
}
</style>
