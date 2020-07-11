<template>
  <div>
    <div>
      <b-jumbotron bg-variant="info" text-variant="black" border-variant="dark">
        <template v-slot:header>About Us</template>

        <hr class="my-4" />
        <div>
          <p>
            Gary Klein started East Central Countertops 13 years ago, and has 39
            years of experience building countertops and cabinets in Mora, MN.
            He is known for his attention to detail and demands the highest
            quality, from the parts you see every day to the parts you'll never
            see. Those years of experience have taught him what works and what
            doesn't, so you can be confident that your custom kitchen or
            bathroom will last for many years to come.
          </p>
        </div>
      </b-jumbotron>
    </div>
  </div>
</template>

<script>
export default {
  name: "Jumbotron",
  components: {},
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
  padding-bottom: 10px;
  margin-bottom: unset !important;
  margin: 20px;
}
</style>
