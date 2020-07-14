<template>
  <div>
    <b-carousel
      id="carousel-fade"
      style="text-shadow: 0px 0px 2px #000"
      fade
      indicators
      img-width="1024"
      img-height="480"
    >
      <b-carousel-slide
        class="slideText"
        alt="kitchen cabinets"
        img-src="../../assets/cabinet-1.jpg"
        text="Custom Cabinets"
      ></b-carousel-slide>
      <b-carousel-slide
        class="slideText"
        alt="kitchen cabinets"
        img-src="../../assets/cabinet-2.jpg"
        text="Custom post-formed laminate countertops"
      ></b-carousel-slide>
      <b-carousel-slide
        class="slideText"
        alt="bathroom cabinets"
        img-src="../../assets/cabinet-3.jpg"
        text="Under-mount Sinks"
      ></b-carousel-slide>
    </b-carousel>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.slideText {
  font-size: 40px;
}
</style>
