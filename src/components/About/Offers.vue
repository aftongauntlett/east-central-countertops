<template>
  <div class="d-flex justify-content-center flex-wrap mb-5">
    <div v-for="offer in offers" :key="offer.title">
      <div>
        <div class="pb-3 pt-5">
          <img :src="offer.image" alt="counter top" />
        </div>
        <div>
          <h4>{{ offer.title }}</h4>
          <div>{{ offer.description }}</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      offers: [
        {
          title: "Laminate Countertops",
          description:
            "We build custom post-formed laminate countertops, creating a seamless backsplash for long-lived durability. We offer a wide variety of high-quality laminates to choose from, including Wilsonart HD. Wilsonart HD laminates are available in numerous patterns and textures, combining antimicrobial protection with enhanced scratch and scuff-resistant AEON™ technology to create countertops up to 5X more durable than Wilsonart's standard laminate and up to 3X more wear resistant than the industry standard.",
          image: require("../../assets/cabinet-1.jpg")
        },
        {
          title: "Custom Cabinets",
          description:
            "We can build custom wood cabinets and shelving for any space, incorporating all the features you want with the quality and durability that you need.",
          image: require("../../assets/cabinet-2.jpg")
        },
        {
          title: "Specialty Features",
          description:
            "We have experience working with a number of specialty features, including under-mount sinks and butcher block tops.",
          image: require("../../assets/cabinet-3.jpg")
        },
        {
          title: "And More!",
          description: "Please contact us for more information.",
          image: require("../../assets/cabinet-4.jpg")
        }
      ]
    };
  },
  components: {}
};
</script>

<style scoped>
.card {
  border: none;
  padding: 15px;
  margin: 15px;
}

img {
  width: 30%;
  height: auto;
}
</style>
