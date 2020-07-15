<template>
  <div>
    <div>
      <div>
        <h2>Services Offered</h2>
        <hr class="my-4" />
        <Offers />
      </div>
    </div>
  </div>
</template>

<script>
import Offers from "../components/About/Offers";
export default {
  name: "About",
  components: {
    Offers
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

.bg-info {
  background-color: white !important;
  border: none !important;
}
</style>
