<template>
  <div class="slow card-area d-flex justify-content-center">
    <b-card title="About Us" tag="article" class="aboutTitle m-md-5 mt-3 p-3">
      <b-card-text>
        Gary Klein started East Central Countertops 13 years ago, and has 39 years of experience building countertops and cabinets in Mora, MN. He is known for his attention to detail and demands the highest quality, from the parts you see every day to the parts you'll never see. Those years of experience have taught him what works and what doesn't, so you can be confident that your custom kitchen or bathroom will last for many years to come.
        <Buttons />
      </b-card-text>
    </b-card>
  </div>
</template>

<script>
import Buttons from "./Buttons";

export default {
  name: "Paragraph",
  components: {
    Buttons
  }
};
</script>

<style scoped>
</style>
