<template>
  <div>
    <div>
      <div>
        <b-jumbotron
          bg-variant="info"
          text-variant="black"
          border-variant="dark"
        >
          <template v-slot:header>Services Offered</template>
          <hr class="my-4" />
          <Offers />
        </b-jumbotron>
      </div>
    </div>
  </div>
</template>

<script>
import Offers from "../components/About/Offers";
export default {
  name: "About",
  components: {
    Offers,
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

.bg-info {
  background-color: white !important;
  border: none !important;
}
</style>
