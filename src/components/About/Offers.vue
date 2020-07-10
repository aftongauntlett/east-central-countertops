<template>
  <div>
    <div class="container d-flex justify-content-center offers slow">
      <div class="row w-500b-5">
        <div v-for="item in offers" :key="item.title">
          <div class="hireTitle pt-3">
            <strong>{{ item.title }}</strong>
          </div>
          <div class="description">{{ item.description }}</div>
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
        },
        {
          title: "Custom Cabinets",
          description:
            "We can build custom wood cabinets and shelving for any space, incorporating all the features you want with the quality and durability that you need.",
        },
        {
          title: "Specialty Features",
          description:
            "We have experience working with a number of specialty features, including under-mount sinks and butcher block tops.",
        },
      ],
    };
  },
  components: {},
};
</script>

<style scoped>
.offers {
  text-align: left;
  line-height: 200%;
  color: rgb(46, 40, 40);
}

.hireTitle:hover {
  font-size: 20px;
}

.hireTitle {
  font-size: 18px;
}

.slow {
  animation: slow 0.5s ease forwards;
}

@keyframes slow {
  from {
    opacity: 0;
  }
  to {
    opacity: 100;
  }
}
</style>
