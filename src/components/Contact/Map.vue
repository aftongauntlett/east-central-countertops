<template>
  <div class="mb-5 mt-3">
    <b-jumbotron class="jumbotron" bg-variant="info" text-variant="black" border-variant="dark">
      <template v-slot:header>Find Us Here:</template>
      <div class="contact">
        <div class="d-flex justify-content-around flex-wrap"></div>
        <hr class="my-4" />
      </div>
      <div class="map-responsive">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2776.269624650274!2d-93.34844828442769!3d45.905918879108604!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x52b3c8ece9648345%3A0xdf7776dae3599af2!2s1814%20220th%20Ave%2C%20Mora%2C%20MN%2055051!5e0!3m2!1sen!2sus!4v1594436567788!5m2!1sen!2sus"
          width="400"
          height="350"
          frameborder="0"
          style="border:0;"
          allowfullscreen
          aria-hidden="false"
          tabindex="0"
        ></iframe>
      </div>
    </b-jumbotron>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.jumbotron {
  padding-bottom: 30px;
  margin-bottom: unset !important;
  background-color: white !important;
  border: none !important;
}

.map-responsive {
  overflow: hidden;
  padding-bottom: 56.25%;
  position: relative;
  height: 0;
}
.map-responsive iframe {
  left: 0;
  top: 0;
  height: 100%;
  width: 100%;
  position: absolute;
}
</style>
